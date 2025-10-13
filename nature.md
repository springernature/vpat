# Nature Accessibility Conformance Report International Edition
(Based on VPAT® Version 2.5Rev)

**Report Date**: 29 July 2025  
**Name of Product/Version**: Nature.com _(we do not version our software)_  
**Product Description**:
Nature.com publishes peer-reviewed research, reviews and news across a number of journals. This report refers entirely to the accessibility of editorial, journal, and magazine web documents published at the top level domain of <a href="http://www.nature.com">www.nature.com</a>, including informational pages, and to all web documents included in account management pages, and the purchasing and subscription process.  
**Contact information**: Please contact your Institutional Sales representative.  
**Notes**:  
**Evaluation Methods Used**: Conformance to the listed accessibility standards has been evaluated by Springer Nature's dedicated Accessibility Specialists. We use a combination of static analysis tools (including but not limited to [axe by Deque](https://www.deque.com/axe/), [WAVE by WebAIM](https://wave.webaim.org/extension/), and all of the tools described in our [Frontend Playbook's Accessibility Guide](https://github.com/springernature/frontend-playbook/blob/main/accessibility/01-popular-tools.md#accessibility-tools)). Our manual testing uses [WCAG-EM](https://www.w3.org/WAI/test-evaluate/conformance/wcag-em/) as its base strategy, and further details are also described in our Frontend Playbook under the "Manual testing" and "Assistive technology" sections.


## Applicable Standards/Guidelines

This report covers the degree of conformance for the following accessibility standard/guidelines:

<table cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td><strong>Standard/Guideline</strong></td>
<td nowrap><strong>Included In Report</strong></td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/2008/REC-WCAG20-20081211/">Web Content Accessibility Guidelines 2.0</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.w3.org/TR/WCAG21">Web Content Accessibility Guidelines 2.1</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.w3.org/TR/WCAG22">Web Content Accessibility Guidelines 2.2</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines">Revised Section 508 standards published January 18, 2017 and corrected January 22, 2018</a></td>
<td nowrap><strong>Yes</strong></td>
</tr>
<tr>
<td><a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.01.01_60/en_301549v030101p.pdf">EN 301 549 Accessibility requirements for ICT products and services - V3.1.1 (2019-11)</a> AND <a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf">EN 301 549 Accessibility requirements for ICT products and services - V3.2.1 (2021-03)</a></td>
<td nowrap><strong>Yes</strong></td>
</tr>
</tbody>
</table>

## Terms

The terms used in the Conformance Level information are defined as follows:

- **Supports**: The functionality of the product has at least one method that meets the criterion without known defects or meets with equivalent facilitation.
- **Partially Supports**: Some functionality of the product does not meet the criterion.
- **Does Not Support**: The majority of product functionality does not meet the criterion.
- **Not Applicable**: The criterion is not relevant to the product.
- **Not Evaluated**: The product has not been evaluated against the criterion. This can be used only in WCAG Level AAA.

## WCAG 2.2 Report

Tables 1 and 2 also document conformance with:
- EN 301 549:
  - Clause 9 - Web
  - Clauses 10.1-10.4 of Clause 10 - Non-Web documents
  - Clauses 11.1-11.4 and 11.8.2 of Clause 11 - Software
  - Clauses 12.1.2 and 12.2.4 of Clause 12 – Documentation and support services
- Revised Section 508:
  - Chapter 5 – 501.1 Scope, 504.2 Content Creation or Editing
  - Chapter 6 – 602.3 Electronic Support Documentation

**Note**: When reporting on conformance with the WCAG 2.1 Success Criteria, they are scoped for full pages, complete processes, and accessibility-supported ways of using technology as documented in the [WCAG 2.2 Conformance Requirements](https://www.w3.org/TR/WCAG22/#conformance-to-wcag-2-2).

### Table 1: Success Criteria, Level A

<table id="WCAG-A">
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all"><strong>1.1.1 Non-text Content</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.1.1 (Web)</li>
<li>10.1.1.1 (Non-web document)</li>
<li>11.1.1.1.1 (Open Functionality Software)</li>
<li>11.1.1.1.2 (Closed Functionality Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
With rare exceptions, most images supplied by Springer Nature provide alternative text, or descriptions, or figure captions. We may use WAI-ARIA techniques to link some complex images with their descriptions if alternative text is unable to provide adequate context.
<br><br>
Background images such as icons on user interface elements are generally identified with visible text labels. Sometimes we may use visually-hidden text or WAI-ARIA techniques instead.
<br><br>
We mark up some images so that they can be ignored by Assistive Technologies if they are <a href="https://www.w3.org/TR/WCAG21/#dfn-pure-decoration"><i>pure decoration</i></a> (as defined by WCAG 2.1).
<br><br>
The <a href="https://www.nature.com/nature/subscribe">Nature subscription pages</a> currently contain SVG images without text alternatives, and decorative SVG images that are not marked up to be ignored by Assistive Technologies. We are actively working to repair these problems.
<br><br>
Third-party scripts may inject non-text content without text alternatives, or with inadequate text alternatives. These include images in advertising scripts. When we become aware of deficiencies, we contact third-party suppliers to request repairs.
<br><br>
When supplied by authors who publish with us, some complex images may lack adequate alternative text, descriptions, and/or captions. Examples may include images of charts, graphs, or maps. Generally, these images are used to supplement text content. A large-scale and currently-active programme of work to improve alternative text content submitted by our authors is under way to address this.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.1 (Web)</li>
<li>10.1.2.1 (Non-web document)</li>
<li>11.1.2.1.1 (Open Functionality Software)</li>
<li>11.1.2.1.2.1 and 11.1.2.1.2.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
This product has a diverse mix of multimedia content, both self-hosted and hosted on third-party sites. Video-only content is generally used to support text-based content.
<br><br>
Audio-only content may be used to support text-based content. Audio-only content may also be used in Podcasts across various journals. Some but not all podcasts provide transcripts.
<br><br>
While Nature Magazine generally provides transcripts and/or text descriptions of multimedia content in new Magazine articles, they may be absent from older Nature Magazine content and journal content supplied by authors who publish with us. We currently have no method of confirming the inclusion of adequate media alternatives or transcripts. 	
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions"><strong>1.2.2 Captions (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.2 (Web)</li>
<li>10.1.2.2 (Non-web document)</li>
<li>11.1.2.2 (Open Functionality Software)</li>
<li>11.1.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
This product has a diverse mix of multimedia content, both self-hosted and hosted on third-party sites. Captions and/or transcripts may be provided for some pre-recorded content, but we currently have no method of confirming the inclusion of transcripts or captions.

While Nature Magazine generally provides captions and/or transcripts for pre-recorded content in new Magazine articles, they may be absent from older Nature Magazine content and journal content supplied by authors who publish with us. We currently have no method of confirming the inclusion of transcripts or captions.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.3 (Web)</li>
<li>10.1.2.3 (Non-web document)</li>
<li>11.1.2.3.1 (Open Functionality Software)</li>
<li>11.1.2.3.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
This product has a diverse mix of multimedia content, both self-hosted and hosted on third-party sites. Audio description is not generally used across our content, but some media may provide media alternatives such as text descriptions of video content.
<br><br>
We currently have no method of confirming the inclusion of adequate media alternatives.
</td>
</tr>
<tr id="info-and-relationships" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic"><strong>1.3.1 Info and Relationships</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.1 (Web)</li>
<li>10.1.3.1 (Non-web document)</li>
<li>11.1.3.1.1 (Open Functionality Software)</li>
<li>11.1.3.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
We generally use progressive enhancement techniques and semantically-correct markup so that information, structure, and relationships can be understood independent of presentation.
<br><br>
We make use of WAI-ARIA roles to support (named) landmarks, and use WAI-ARIA roles and properties when required for more complex functionality such as popup menus and dialogs. We do not use WAI-ARIA where it is not required.
<br><br>
Some functionality may omit required WAI-ARIA roles, states, or attributes, or misuse WAI-ARIA markup and techniques. When we become aware of content with these problems, we immediately take steps to repair the issues.
<br><br>
Third-party scripts may inject content with incorrect or absent information about structure and relationships. These include content in advertising scripts, among others.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence"><strong>1.3.2 Meaningful Sequence</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.2 (Web)</li>
<li>10.1.3.2 (Non-web document)</li>
<li>11.1.3.2.1 (Open Functionality Software)</li>
<li>11.1.3.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>
The meaning of the content in the pages of this product does not depend on the order of the sections.
<br><br>
We use semantically-correct markup to allow Assistive Technologies to interpret the meaning of content and controls within each section.
</td>
</tr>
<tr valign="top">
<td><strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding">1.3.3 Sensory Characteristics</a></strong> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.3 (Web)</li>
<li>10.1.3.3 (Non-web document)</li>
<li>11.1.3.3 (Open Functionality Software)</li>
<li>11.1.3.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
The pages of this product do not depend solely on sensory characteristics such as shape, size, visual location, orientation, or sound to understand content.
<br><br>
Icons may be displayed to control functionality, but adjacent visible text labels or (less commonly) WAI-ARIA labels are also provided to ensure that relationships are available to Assistive Technologies.
<br><br>
When supplied by authors who publish with us, some complex images may rely on sensory characteristics to be understood. Examples may include images of charts, graphs, or maps. Generally, these images are used to supplement text content.
</td>
</tr>
<tr id="use-of-color" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color"><strong>1.4.1 Use of Color</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.1 (Web)</li>
<li>10.1.4.1 (Non-web document)</li>
<li>11.1.4.1 (Open Functionality Software)</li>
<li>11.1.4.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Colour alone is not used to convey information in the pages of this product.
<br><br>
Links and icons may use colour to indicate hover or active states. These are supplemented with visible focus rings and/or text decoration underlines and/or luminosity differences per WAI advisory techniques <a href="https://www.w3.org/WAI/WCAG21/Techniques/general/G183">G183</a> and <a href="https://www.w3.org/WAI/WCAG21/Techniques/css/C15">C15</a>.
<br><br>
When supplied by authors who publish with us, some complex images may rely on colour as the only visual means of understanding information. Examples may include images of charts, graphs, or maps. Generally, these images are used to supplement text content.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio"><strong>1.4.2 Audio Control</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.2 (Web)</li>
<li>10.1.4.2 (Non-web document)</li>
<li>11.1.4.2 (Open Functionality Software)</li>
<li>11.1.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>
Content supplied by us does not play automatically. All audio files supplied by us, either hosted on our own platform or through a third party, have mechanisms for pausing, stopping, and controlling volume.
</td>
</tr>
<tr id="keyboard" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable"><strong>2.1.1 Keyboard</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.1 (Web)</li>
<li>10.2.1.1 (Non-web document)</li>
<li>11.2.1.1.1 (Open Functionality Software)</li>
<li>11.2.1.1.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>
Partially Supports
</td>
<td>
All first-party components in this product can be navigated by keyboard alone. Complex elements like flyout menus can be exited with the <kbd>esc</kbd> key. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Third-party advertising scripts may inject content that cannot be interacted with easily or at all by keyboard.
<br><br>
Other types of third-party content such as customer services widgets may be difficult to use with keyboard alone. When we become aware of deficiencies, we contact third-party suppliers to request repairs. Additionally, where possible, we aim to provide equivalent alternatives to problematic content.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping"><strong>2.1.2 No Keyboard Trap</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.2 (Web)</li>
<li>10.2.1.2 (Non-web document)</li>
<li>11.2.1.2 (Open Functionality Software)</li>
<li>11.2.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Keyboard trapping inside components on the pages of this product is rare, and in most cases is managed appropriately, allowing focus to be moved away from any component using standard keystrokes (<kbd>tab</kbd>, <kbd>shift</kbd>, <kbd>esc</kbd>).
<br><br>
Third-party content such as survey modal dialogs may trap focus and provide inadequate methods of escaping. When we become aware of deficiencies, we contact third-party suppliers to request repairs.
</td>
</tr>
<tr id="character-key-shortcuts" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#character-key-shortcuts"><strong>2.1.4 Character Key Shortcuts</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.4 (Web)</li>
<li>10.2.1.4 (Non-web document)</li>
<li>11.2.1.4.1 (Open Functionality Software)</li>
<li>11.2.1.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Not Applicable</td>
<td>This product does not implement character key shortcuts.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors"><strong>2.2.1 Timing Adjustable</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2.1 (Web)</li>
<li>10.2.2.1 (Non-web document)</li>
<li>11.2.2.1 (Open Functionality Software)</li>
<li>11.2.2.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Not applicable</td>
<td>No time limits are set by the content in the pages of this product.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-pause"><strong>2.2.2 Pause, Stop, Hide</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2.2 (Web)</li>
<li>10.2.2.2 (Non-web document)</li>
<li>11.2.2.2 (Open Functionality Software)</li>
<li>11.2.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Any moving, blinking or scrolling content on this product generally does not start automatically, and is complemented by controls that allow users to pause or otherwise stop the content. Moving images in the form of gifs may not meet this criterion.  
<br><br>
Automatically updating information is rare on this product. Third-party advertising scripts may inject content that automatically moves or blinks and lasts more than five seconds, without providing a mechanism to pause, stop, or hide that content.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate"><strong>2.3.1 Three Flashes or Below Threshold</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.3.1 (Web)</li>
<li>10.2.3.1 (Non-web document)</li>
<li>11.2.3.1 (Open Functionality Software)</li>
<li>11.2.3.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>The pages of this product do not contain anything that flashes.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip"><strong>2.4.1 Bypass Blocks</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.1 (Web)</li>
<li>10.2.4.1 (Non-web document) – Does not apply</li>
<li>11.2.4.1 (Open Functionality Software) – Does not apply</li>
<li>11.2.4.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Partially Supports</td>
<td>
We use semantically-correct markup so that Assistive Technology users can recognise elements and move around them accordingly. We make use of HTML and WAI-ARIA roles to support landmarks. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Some third-party content, for example embedded widgets that provide alternative means of exploring data, may prevent users from being able to bypass repetitive information. When we become aware of deficiencies, we contact third-party suppliers to request repairs.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title"><strong>2.4.2 Page Titled</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.2 (Web)</li>
<li>10.2.4.2 (Non-web document)</li>
<li>11.2.4.2 (Open Functionality Software) - Does not apply</li>
<li>11.2.4.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>
The pages on this product have unique page titles that describe the purpose of the page.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order"><strong>2.4.3 Focus Order</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.3 (Web)</li>
<li>10.2.4.3 (Non-web document)</li>
<li>11.2.4.3 (Open Functionality Software)</li>
<li>11.2.4.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
The meaning or operation of the pages on this product is generally unaffected by focus order. Additionally, in most cases, the focus order of all page content matches the visual order.
<br><br>
On Nature Outlook pages built with Shorthand, collapsing the main navigation into a hamburger menu may disrupt the focus order, making it harder for keyboard users to access navigation links.
<br><br>
Third-party scripts including advertising scripts or survey or customer services widgets (among others), may inject content where the focus order does not match the visual order. The operation and meaning of these components should be unaffected by the focus order.
</td>
</tr>
<tr id="link-purpose-in-context" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs"><strong>2.4.4 Link Purpose (In Context)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.4 (Web)</li>
<li>10.2.4.4 (Non-web document)</li>
<li>11.2.4.4 (Open Functionality Software)</li>
<li>11.2.4.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Generally, the purpose of first-party links can be determined by their descriptive text labels. Links that are not primarily text-based (e.g. images or icons) have alternative accessible text or supplementary text labels.
<br><br>
In submitted articles, anchor links that refer to supplementary figures or tables may have insufficient context in their link text (e.g. figure numbers only). In limited cases we may support inadequate link text with the use of WAI-ARIA techniques. We are actively working to repair these problems.
<br><br>
Third-party scripts including advertising scripts, survey or customer services widgets (among others), may inject content that includes links with no accessible text, or poorly-named accessible text. When we become aware of deficiencies, we contact third-party suppliers to request repairs.
</td>
</tr>
<tr id="pointer-gestures" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-gestures"><strong>2.5.1 Pointer Gestures</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.1 (Web)</li>
<li>10.2.5.1 (Non-web document)</li>
<li>11.2.5.1 (Open Functionality Software)</li>
<li>11.2.5.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>This product generally does not contain any functionality that uses multipoint or path-based gestures for operation.
<br>
<br>
Special feature content may use multipoint gestures for functionality such as pan and zoom controls. Alternatives to multipoint gestures are provided, including single point and keyboard controls. For complex functionality, simple instructions may be provided to explain the available options.
</td>
</tr>
<tr id="pointer-cancellation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-cancellation"><strong>2.5.2 Pointer Cancellation</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.2 (Web)</li>
<li>10.2.5.2 (Non-web document)</li>
<li>11.2.5.2 (Open Functionality Software)</li>
<li>11.2.5.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>All functionality that can be operated using a single pointer can also be cancelled using standard browser and operating system methods.</td>
</tr>
<tr id="label-in-name" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#label-in-name"><strong>2.5.3 Label in Name</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.3 (Web)</li>
<li>10.2.5.3 (Non-web document)</li>
<li>10.2.5.3 (Open Functionality Software)</li>
<li>11.2.5.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>
In most cases where controls contain visible text, that text is also the label for the control. Some third-party scripts may inject content that does not meet this criterion. Supplementary pages (such as special features or marketing pages) may fail to meet this criterion.
</td>
</tr>
<tr id="motion-actuation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#motion-actuation"><strong>2.5.4 Motion Actuation</strong></a> (Level A 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.4 (Web)</li>
<li>10.2.5.4 (Non-web document)</li>
<li>11.2.5.4 (Open Functionality Software)</li>
<li>11.2.5.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Not Applicable</td>
<td>This product does not contain any functionality that can be operated by device motion or user motion.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id"><strong>3.1.1 Language of Page</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.1.1 (Web)</li>
<li>10.3.1.1 (Non-web document)</li>
<li>11.3.1.1.1 (Open Functionality Software)</li>
<li>11.3.1.1.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>
All of the pages in this product use the language attribute on the HTML element to specify the default language of the page.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus"><strong>3.2.1 On Focus</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.1 (Web)</li>
<li>10.3.2.1 (Non-web document)</li>
<li>11.3.2.1 (Open Functionality Software)</li>
<li>11.3.2.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>On search results pages, the sorting radio buttons initiate a change of context when they receive focus. This can prevent users who rely on Assistive Technology from moving past the elements without triggering a change of context.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change"><strong>3.2.2 On Input</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.2 (Web)</li>
<li>10.3.2.2 (Non-web document)</li>
<li>11.3.2.2 (Open Functionality Software)</li>
<li>11.3.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>On search results pages, the sorting radio buttons initiate a change of context when they are selected and without warning. Users with cognitive disabilities or users who rely on Assistive Technology may find the change of context confusing and difficult to process.</td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#consistent-help"><strong>3.2.6 Consistent Help</strong></a> (Level A 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td>Partially Supports</td>
<td>This product generally offers consistent options or information for users to access help, with rare exceptions.
<br><br>
A "Contact us" link is consistently available in the Nature.com footer.
<br><br>
Nature Outlook pages built on Shorthand may not offer consistent options or information for users to access help.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-identified"><strong>3.3.1 Error Identification</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.1 (Web)</li>
<li>10.3.3.1 (Non-web document)</li>
<li>11.3.3.1.1 (Open Functionality Software)</li>
<li>11.3.3.1.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Where user input errors are automatically detected by our own software, those errors are identified with warning text adjacent to the input field. We do not rely on visual characteristics alone (e.g. colour).
<br><br>
Checkout process pages rely solely on built-in browser error checking, and do not identify errors in text. Some users with and without Assistive Technology may be unable to access these error states.
<br><br>
Third-party scripts that accept user input may automatically detect errors but fail to present the errors to users in text. They may rely on visual characteristics alone to indicate user input errors, or place error text in locations that are difficult for screen reader users to access. When we become aware of deficiencies, we contact third-party suppliers to request repairs.
</td>
</tr>
<tr id="labels-or-instructions" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues"><strong>3.3.2 Labels or Instructions</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.2 (Web)</li>
<li>10.3.3.2 (Non-web document)</li>
<li>11.3.3.2 (Open Functionality Software)</li>
<li>11.3.3.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>
Visible and appropriately associated labels are provided for input fields. In limited cases, a visually-hidden label may be provided instead, but we prefer to avoid this pattern.
<br><br>
</td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#redundant-entry"><strong>3.3.7 Redundant Entry</strong></a> (Level A 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td>Supports</td>
<td>This product does not require users to enter information more than once in the process without the information being available for the user to select. Checkout pages include a checkbox to populate inputs with the same values as previously entered (e.g. where the billing address and shipping address is the same).</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses"><strong>4.1.1 Parsing</strong></a> (Level A)
<br><br>Applies to:<br><br>
<em>WCAG 2.0 and 2.1 - Supports</em><br><br>
<em>WCAG 2.2 (obsolete and removed) - Does not apply</em><br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.1 (Web)</li>
<li>10.4.1.1 (Non-web document)</li>
<li>11.4.1.1.1 (Open Functionality Software)</li>
<li>11.4.1.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
The pages of this product generally use semantically-correct markup that meets the HTML5 specification for interface elements. Some very old archived content may occasionally contain unclosed or illegally nested elements.
<br><br>
Third party advertising scripts may inject content that omits start and end tags, contains duplicate attributes or contains illegally nested elements. When we become aware of active advertisements with these problems, we immediately take steps to remove those advertisements from our pages.
</td>
</tr>
<tr id="name-role-value" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv"><strong>4.1.2 Name, Role, Value</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.2 (Web)</li>
<li>10.4.1.2 (Non-web document)</li>
<li>11.4.1.2.1 (Open Functionality Software)</li>
<li>11.4.1.2.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
The pages of this product generally use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
WAI-ARIA attributes may be omitted where they would be useful, for example to support HTML5 features that are not widely supported by client technology. In other cases WAI-ARIA roles or attributes may be misused in ways that cause elements to have misleading semantics. We are actively working to find and repair these problems.
<br><br>
Other third party scripts, including the Disqus commenting widget, may present interactive elements such as tooltips that lack adequate names and roles, making them difficult for screen reader users to access. When we become aware of deficiencies, we contact third party suppliers to request repairs.
</td>
</tr>
</tbody>
</table>

### Table 2: Success Criteria, Level AA

<table id="WCAG-AA">
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions"><strong>1.2.4 Captions (Live)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.4 (Web)</li>
<li>10.1.2.4 (Non-web document)</li>
<li>11.1.2.4 (Open Functionality Software)</li>
<li>11.1.2.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Not Applicable</td>
<td>We do not publish live video.</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only"><strong>1.2.5 Audio Description (Prerecorded)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.5 (Web)</li>
<li>10.1.2.5 (Non-web document)</li>
<li>11.1.2.5 (Open Functionality Software)</li>
<li>11.1.2.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Does Not Support</td>
<td>We do not generally provide audio description for prerecorded video. A limited form of audio description may be provided for some pre-recorded content, but we currently have no method of confirming the inclusion of audio description. </td>
</tr>
<tr id="orientation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#orientation"><strong>1.3.4 Orientation</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.4 (Web)</li>
<li>10.1.3.4 (Non-web document)</li>
<li>11.1.3.4 (Open Functionality Software)</li>
<li>11.1.3.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>This product does not contain any content that restricts its view and operation to a single display orientation, such as portrait or landscape.</td>
</tr>
<tr id="identify-input-purpose" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#identify-input-purpose"><strong>1.3.5 Identify Input Purpose</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.5 (Web)</li>
<li>10.1.3.5 (Non-web document)</li>
<li>11.1.3.5 (Open Functionality Software)</li>
<li>11.1.3.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>
A limited number of form fields may have autocomplete values that allow the field purpose to be determined programmatically, but we have not widely implemented this functionality.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast"><strong>1.4.3 Contrast (Minimum)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.3 (Web)</li>
<li>10.1.4.3 (Non-web document)</li>
<li>11.1.4.3 (Open Functionality Software)</li>
<li>11.1.4.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Generally, all text and images of text supplied by us on the pages of this product have a contrast ratio of at least 4.5:1.
<br><br>
Some placeholder text (e.g. on checkout process pages) may have insufficient contrast. We are actively working to find and repair these problems.
<br><br>
Third party advertising scripts may inject content with insufficient contrast.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale"><strong>1.4.4 Resize text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.4 (Web)</li>
<li>10.1.4.4 (Non-web document)</li>
<li>11.1.4.4.1 (Open Functionality Software)</li>
<li>11.1.4.4.2 (Closed Software)</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
All first party text on the pages of this product can be resized up to 400% without loss of information or functionality.
<br><br>
Third party scripts (for example advertisements) may inject non-responsive content that loses or obscures information when text is resized.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation"><strong>1.4.5 Images of Text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.5 (Web)</li>
<li>10.1.4.5 (Non-web document)</li>
<li>11.1.4.5.1 (Open Functionality Software)</li>
<li>11.1.4.5.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Outside of editorial content managed by content management system (CMS), the contents of author-submitted published books and papers, and third party scripts, the pages of this product do not use images of text to convey information except in the case of <a href="https://www.w3.org/WAI/WCAG21/Understanding/images-of-text.html">logotypes</a> (considered essential per WCAG 2.1) or when the image is <a href="https://www.w3.org/TR/WCAG21/#dfn-pure-decoration">pure decoration</a>.
<br><br>
CMS content and published books and papers may include complex images that contain images of text. In most cases these images are used to supplement the text content they appear alongside. In some cases (e.g. charts, graphs, or maps, among others), the text content presented alongside may be insufficient to explain the contents of the image. A large-scale and currently-active programme of work to improve alternative text content submitted by our authors is under way to address this.
<br><br>
Third party advertising scripts may inject images containing images of text.
</td>
</tr>
<tr id="reflow" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#reflow"><strong>1.4.10 Reflow</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.10 (Web)</li>
<li>10.1.4.10 (Non-web document)</li>
<li>11.1.4.10.1 (Open Functionality Software)</li>
<li>11.1.4.10.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>All parts of this product are responsive. Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions, except where necessary.

Examples of necessary exclusions that are permitted under the guidelines include the display of large tables or figures - in these cases we provide an additional "full screen" view so that more data can be visible at once.
<br><br>
Third party scripts (e.g. advertising, customer services widgets) may inject content that fails to meet this criterion. When we become aware of deficiencies, we immediately take steps to request repairs from third party vendors.
</td>
</tr>
<tr id="non-text-contrast" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#non-text-contrast"><strong>1.4.11 Non-text Contrast</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.11 (Web)</li>
<li>10.1.4.11 (Non-web document)</li>
<li>11.1.4.11 (Open Functionality Software)</li>
<li>11.1.4.11 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>
The visual presentation of User Interface Components in this product have a contrast ratio of at least 3:1 against adjacent colours.
<br><br>
When supplied by authors who publish with us, Graphical Objects (e.g. charts, graphs, or maps, among others) may have inadequate contrast.
<br><br>
Third party content (e.g. advertising, customer services widgets) may inject non-text elements with inadequate contrast. When we become aware of deficiencies, we immediately take steps to request repairs from third party vendors.
</td>
</tr>
<tr id="text-spacing" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#text-spacing"><strong>1.4.12 Text Spacing</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.12 (Web)</li>
<li>10.1.4.12 (Non-web document)</li>
<li>11.1.4.12 (Open Functionality Software)</li>
<li>11.1.4.12 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>No loss of content or functionality occurs by setting the text spacing properties specified by this criterion anywhere in this product.
<br><br>
Third party content (e.g. advertising, customer services widgets) may inject elements that fail to meet this criterion. When we become aware of deficiencies, we immediately take steps to request repairs from third party vendors.
</td>
</tr>
<tr id="content-on-hover-or-focus" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#content-on-hover-or-focus"><strong>1.4.13 Content on Hover or Focus</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.13 (Web)</li>
<li>10.1.4.13 (Non-web document)</li>
<li>11.1.4.13 (Open Functionality Software)</li>
<li>11.1.4.13 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>Additional content that becomes visible on hover or focus (for example tooltips) is extremely rare in this product. In all cases where content is initially hidden and displayed on interaction, we trigger that display with explicit, unambiguous input such as a click or keypress. Content is persistently visible until dismissed by a similarly unambiguous interaction. We never rely on hover alone.  
<br><br>
Third party content (e.g. advertising, customer services widgets) may inject elements that fail to meet this criterion. When we become aware of deficiencies, we immediately take steps to request repairs from third party vendors.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc"><strong>2.4.5 Multiple Ways</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.5 (Web)</li>
<li>10.2.4.5 (Non-web document) – Does not apply</li>
<li>11.2.4.5 (Open Functionality Software) – Does not apply</li>
<li>11.2.4.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Supports</td>
<td>Users may use the search function or the provided links to access any part of this product. Breadcrumb menus are provided to return users to the index page. The main navigation component can also be used to access the main subject index pages.</td>
</tr>
<tr id="headings-and-labels" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive"><strong>2.4.6 Headings and Labels</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.6  (Web)</li>
<li>10.2.4.6 (Non-web document)</li>
<li>11.2.4.6 (Open Functionality Software)</li>
<li>11.2.4.6 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Our document structure is semantically marked up using headings to create a sequential hierarchy of content. Rarely, headings or labels may be visually hidden but available to Assistive Technologies, though we prefer to keep this pattern to a minimum.
<br><br>
Nature magazine and a limited number of journals publish editorial content from a content management system (CMS). Content generated by CMS may occasionally lack appropriate headings (e.g. using bold text as implicit headings instead of semantically-marked up heading elements).
<br><br>
Other third party scripts, including survey or customer services widgets, may inject content with inadequate or inappropriate headings or labels. When we become aware of deficiencies, we contact third party suppliers to request repairs.
</td>
</tr>
<tr id="focus-visible" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible"><strong>2.4.7 Focus Visible</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.7 (Web)</li>
<li>10.2.4.7 (Non-web document)</li>
<li>11.2.4.7 (Open Functionality Software)</li>
<li>11.2.4.7 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Generally, we provide high-visibility yellow focus rings on all focusable elements. Some items (such as links) may use changes in text-decoration to indicate focus in addition to the focus ring.
<br><br>
Some pages (e.g. some checkout process pages) use default focus rings only. On some of these pages, the default focus ring has been removed from input elements and replaced with a different focus style that provides inadequate visibility. Some components on checkout process pages remove focus styles. We are actively working to repair these problems; the high-visibility focus ring across the majority of this product is intended to be the default.
<br><br>
Third party scripts, including advertising, may inject components that remove focus styles.
</td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum"><strong>2.4.11 Focus Not Obscured (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td></td>
<td></td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#dragging-movements"><strong>2.5.7 Dragging Movements</strong></a> (Level AA 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td></td>
<td></td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#target-size-minimum"><strong>2.5.8 Target Size (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td></td>
<td></td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id"><strong>3.1.2 Language of Parts</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.1.2 (Web)</li>
<li>10.3.1.2 (Non-web document)</li>
<li>11.3.1.2 (Open Functionality Software) – Does not apply</li>
<li>11.3.1.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Does Not Support</td>
<td>Language of Parts is not applicable for the majority of this content. All first-party components on the pages of this product that are part of dynamic templates are written in English.
<br><br>
Editorial content or published papers may be written in or include text in languages other than English. Article content may be marked up with a separate <code>lang</code> attribute that matches the written language, though this is not consistently applied.
<br><br>
Third party scripts may inject components with non-English text - for example a targeted advertisement or file presented in a file viewer (e.g. Figshare) may use a different language to the main document. These may not be marked up with a separate <code>lang</code> attribute.
<br><br>
We currently have no method of confirming the inclusion of appropriate <code>lang</code> attributes for pieces of text in content that may use a different language to the main document.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations"><strong>3.2.3 Consistent Navigation</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.3 (Web)</li>
<li>10.3.2.3 (Non-web document) – Does not apply</li>
<li>11.3.2.3 (Open Functionality Software) – Does not apply</li>
<li>11.3.2.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Supports</td>
<td>
Navigational mechanisms that are repeated on multiple Web pages within the this product website occur in the same relative order each time they are repeated. Although some older archive content on this product may be rendered in older design templates, the navigation of each of these sets of pages is internally consistent.
<br><br>
Pages that deal with sensitive information (including checkout process pages and account management pages) have intentionally simpler designs, and do not share the same navigation system as the main site. The navigation of each of these sets of pages is internally consistent.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality"><strong>3.2.4 Consistent Identification</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.4 (Web)</li>
<li>10.3.2.4 (Non-web document) – Does not apply</li>
<li>11.3.2.4 (Open Functionality Software) – Does not apply</li>
<li>11.3.2.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs) – Does not apply to non-web docs</li>
</ul></td>
<td>Supports</td>
<td>
Components that have the same functionality within a set of Web pages are identified consistently. Although some older archive content on this product may be rendered in older design templates, the identification of components in each of these sets of pages is internally consistent.
<br><br>
Pages that deal with sensitive information (including checkout process pages and account management pages) have intentionally simpler designs. The presentation of each of these sets of pages is internally consistent, and the tasks performed are unlike those performed elsewhere on the site.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions"><strong>3.3.3 Error Suggestion</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.3 (Web)</li>
<li>10.3.3.3 (Non-web document)</li>
<li>11.3.3.3 (Open Functionality Software)</li>
<li>11.3.3.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Partially Supports</td>
<td>
Where user input errors are automatically detected by our own software, those errors are identified with warning text adjacent to the input field. Unless it would present a risk to security, the warning text describes the error and what the user should do to correct it.
<br><br>
Third party scripts including the Disqus commenting widget, or other widgets that accept user input, may automatically detect errors but fail to present the errors to users in ways that they can perceive. They may rely on visual characteristics alone to indicate user input errors, or place error text in locations that are difficult for screen reader users to access. When we become aware of deficiencies, we contact third party suppliers to request repairs.
</td>
</tr>
<tr valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.4 (Web)</li>
<li>10.3.3.4 (Non-web document)</li>
<li>11.3.3.4 (Open Functionality Software)</li>
<li>11.3.3.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
<li>504.2 (Authoring Tool)</li>
<li>602.3 (Support Docs)</li>
</ul></td>
<td>Supports</td>
<td>The checkout process includes a pre-payment verification page. The user must confirm that their choices are correct on the verification page before they may enter their payment details. At this stage they may return to a previous step to make corrections, cancel, or abandon the process.</td>
</tr>
<tr valign="top">
<td><a href="https://www.w3.org/TR/WCAG22/#accessible-authentication-minimum"><strong>3.3.8 Accessible Authentication (Minimum)</strong></a> (Level AA 2.2 only)
<br><br>
<em>EN 301 549 Criteria - Does not apply</em><br><br>
<em>Revised Section 508 - Does not apply</em>
</td>
<td></td>
<td></td>
</tr>
<tr id="status-messages" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#status-messages"><strong>4.1.3 Status Messages</strong></a> (Level AA 2.1 and 2.2)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.3 (Web)</li>
<li>10.4.1.3 (Non-web document)</li>
<li>11.4.1.3 (Open Functionality Software)</li>
<li>11.4.1.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Does not support</td>
<td>Status messages that do not receive focus are presented in text. These are generally not marked up with programmatic roles to indicate their purpose.</td>
</tr>
</tbody>
</table>

### Table 3: Success Criteria, Level AAA

Notes: This product has not been evaluated for WCAG 2.x Level AAA conformance.

## Revised Section 508 Report

### Chapter 3: [Functional Performance Criteria](https://www.access-board.gov/ict/#chapter-3-functional-performance-criteria) (FPC)

<table>
<thead>
<tr>
<th scope="col"><strong>Criteria</strong></th>
<th scope="col"><strong>Conformance Level</strong></th>
<th scope="col"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>302.1 Without Vision</td>
<td>Partially Supports</td>
<td>The majority of content is marked up for Assistive Technology. Third party scripts may inject content with inadequate accessible alternatives.</td>
</tr>
<tr>
<td>302.2 With Limited Vision</td>
<td>Partially Supports</td>
<td>Markup is written with support for assistive technology. Text is resizable by the user. Fonts are set as rems and use pixels as a fallback if not supported. The product does not impede the user from zooming into the page. Third party scripts may inject content with inadequate accessibility support.</td>
</tr>
<tr>
<td>302.3 Without Perception of Color</td>
<td>Supports</td>
<td>Color perception is not generally needed to use this product.</td>
</tr>
<tr>
<td>302.4 Without Hearing</td>
<td>Partially Supports</td>
<td>Some but not all audio is supported by captions or transcripts.</td>
</tr>
<tr>
<td>302.5 With Limited Hearing</td>
<td>Partially Supports</td>
<td>Some but not all audio is supported by captions or transcripts.</td>
</tr>
<tr>
<td>302.6 Without Speech</td>
<td>Not Applicable</td>
<td>Speech is not needed to use this product.</td>
</tr>
<tr>
<td>302.7 With Limited Manipulation</td>
<td>Partially Supports</td>
<td>This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Fine motor control and simultaneous actions are not required to operate this product. Third party scripts may inject content that is difficult to use without a pointing device.</td>
</tr>
<tr>
<td>302.8 With Limited Reach and Strength</td>
<td>Partially Supports</td>
<td>This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Third party scripts may inject content that is difficult to use without a pointing device.</td>
</tr>
<tr>
<td>302.9 With Limited Language, Cognitive, and Learning Abilities</td>
<td>Partially Supports</td>
<td>The pages of this product generally have a consistent presentation with clear labels, titles, and accessible names for controls. Third party scripts may inject content with inconsistent or absent labelling of interface components.</td>
</tr>
</tbody>
</table>

### Chapter 4: [Hardware](https://www.access-board.gov/ict/#chapter-4-hardware)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter 5: [Software](https://www.access-board.gov/ict/#chapter-5-software)

<table>
<thead>
<tr>
<th scope="col" id="chap-5-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-5-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-5-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>501.1 Scope – Incorporation of WCAG 2.1 AA</td>
<td>See <a href="#wcag-21-report">WCAG 2.1</a> section</td>
<td>See information in WCAG section</td>
</tr>
<tr>
<th scope="column" colspan="3" id="502-interop"> <a href="https://www.access-board.gov/ict/#502-interoperability-assistive-technology">502 Interoperability with Assistive Technology</a></th>
</tr>
<tr>
<td headers="502-interop chap-5-criteria">502.2.1 User Control of Accessibility Features</td>
<td headers="502-interop chap-5-conformance">Not Applicable</td>
<td headers="502-interop chap-5-remarks">This product is not considered platform software as defined by Section 508. See <a href="https://www.access-board.gov/ict/#E103.4">E103 Definitions, section E103.4</a>.</td>
</tr>
<tr>
<td headers="502-interop chap-5-criteria">502.2.2 No Disruption of Accessibility Features</td>
<td headers="502-interop chap-5-conformance">Not Applicable</td>
<td headers="502-interop chap-5-remarks">
This product has no platform features as defined by Section 508. The product is compatible with operating system and browser accessibility features configured by the user.
<br><br>
Third party scripts may inject content that disrupts standard operating system and browser accessibility features. See information in WCAG section for complete details.
</td>
</tr>
<tr>
<th scope="column" colspan="3" id="502-services">502.3 Accessibility Services</th>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.1 Object Information</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
Object role, state(s), properties, boundary, name, and description are generally programmatically determinable.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.2 Modification of Object Information</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
The pages of this product use standard HTML or WAI-ARIA object roles for maximum compatibility with Assistive Technologies.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.3 Row, Column, and Headers</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
Data tables in original research or editorial content may not be marked up with adequate table header information.
<br><br>
Data tables in dynamic templates are rare, but where they do appear, they are marked up with standard HTML table elements. Row headers are present and associated with rows and columns as necessary.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.4 Values</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.5 Modification of Values</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.6 Label Relationships</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">
The pages in this product use labels on components that require user input.
<br><br>
See WCAG sections <a href="#headings-and-labels">2.4.6 Headings and Labels</a> and <a href="#labels-or-instructions">3.3.2 Labels or Instructions</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.7 Hierarchical Relationships</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
The pages of this product generally use standard HTML to express hierarchy. Third party scripts may inject content that obscures the relationships between components.
<br><br>
See WCAG section <a href="#info-and-relationships">1.3.1 Info and Relationships</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.8 Text</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
The pages of this product use standard plain text in HTML.
<br><br>
Original research or editorial content may contain images of text without adequate programmatically determinable alternatives.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.9 Modification of Text</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">The pages of this product use standard HTML for user input.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.10 List of Actions</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.11 Actions on Objects</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.
<br><br>
Some third party scripts may inject content that cannot be interacted with easily or at all by keyboard or by some Assistive Technologies.
<br><br>
See WCAG section <a href="#keyboard">2.1.1 Keyboard</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.12 Focus Cursor</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
We provide focus styles on most focusable elements. Third party scripts may inject components that remove focus styles or alter focus in a way that makes them difficult to perceive by all users.
<br><br>
See WCAG sections <a href="#use-of-color">1.4.1 Use of Color</a> and <a href="#focus-visible">2.4.7 Focus Visible</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.13 Modification of Focus Cursor</td>
<td headers="502-services chap-5-conformance">Supports</td>
<td headers="502-services chap-5-remarks">The pages of this product use standard HTML elements and cursor controls for user input that may be overridden by Assistive Technology.</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.3.14 Event Notification</td>
<td headers="502-services chap-5-conformance">Partially Supports</td>
<td headers="502-services chap-5-remarks">
The pages of this product use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
Rarely, components may omit or misuse WAI-ARIA attributes in a way that prevents users of some Assistive Technologies from being able to perceive changes in state. We are actively working to find and repair these problems.
<br><br>
Some third party scripts may inject content that fails to notify users of changes in state.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td headers="502-services chap-5-criteria">502.4 Platform Accessibility Features</td>
<td headers="502-services chap-5-conformance">Not Applicable</td>
<td headers="502-services chap-5-remarks">This product is not considered platform software as defined by Section 508. See <a href="https://www.access-board.gov/ict/#E103.4">E103 Definitions, section E103.4</a>.</td>
</tr>
<tr>
<th scope="column" colspan="3"id="503-apps"><a href="https://www.access-board.gov/ict/#503-applications">503 Applications</a></th>
</tr>
<tr>
<td headers="503-apps chap-5-criteria">503.2 User Preferences</td>
<td headers="503-apps chap-5-conformance">Supports</td>
<td headers="503-apps chap-5-remarks">This product does not override user selected contrast and color selections and other individual display attributes.</td>
</tr>
<tr>
<td headers="503-apps chap-5-criteria">503.3 Alternative User Interfaces</td>
<td headers="503-apps chap-5-conformance">Not Applicable</td>
<td headers="503-apps chap-5-remarks">We do not provide any alternative user interface for this product that functions as assistive technology.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="503-usercon">503.4 User Controls for Captions and Audio Description</th>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.1 Caption Controls</td>
<td headers="503-usercon chap-5-conformance">Partially Supports</td>
<td headers="503-usercon chap-5-remarks">Not all video content provides captions. Where captions are provided, the controls for adjusting those captions are found at the same menu level as the user controls for volume or program selection.</td>
</tr>
<tr>
<td headers="503-usercon chap-5-criteria">503.4.2 Audio Description Controls</td>
<td headers="503-usercon chap-5-conformance">Does Not Support</td>
<td headers="503-usercon chap-5-remarks"Audio description is not generally used across our content.</td>
</tr>
<tr>
  <th scope="column" colspan="3" id="504-authoring"><a href="https://www.access-board.gov/ict/#504-authoring-tools">504 Authoring Tools</a></th>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2 Content Creation or Editing (if not authoring tool, enter “not applicable”)</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2.1 Preservation of Information Provided for Accessibility in Format Conversion</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.2.2 PDF Export</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.3 Prompts</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="504-authoring chap-5-criteria">504.4 Templates</td>
<td headers="504-authoring chap-5-conformance">Not Applicable</td>
<td headers="504-authoring chap-5-remarks">This product is not used as an authoring tool.</td>
</tr>
</tbody>
</table>

### Chapter 6: [Support Documentation and Services](https://www.access-board.gov/ict/#chapter-6-support-documentation-and-services)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

## EN 301 549 Report

### Clause 4: [4.2 Functional Performance Statements](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=20) (FPS)

<table>
<thead>
<tr>
<th scope="col"><strong>Criteria</strong></th>
<th scope="col"><strong>Conformance Level</strong></th>
<th scope="col"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>4.2.1 Usage without vision</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.1</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.1</td>
</tr>
<tr>
<td>4.2.2 Usage with limited vision</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.2</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.2</td>
</tr>
<tr>
<td>4.2.3 Usage without Perception of Color</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.3</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.3</td>
</tr>
<tr>
<td>4.2.4 Usage without hearing</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.4</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.4</td>
</tr>
<tr>
<td>4.2.5 Usage with limited hearing</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.5</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.5</td>
</tr>
<tr>
<td>4.2.6 Usage without vocal capability</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.6</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.6</td>
</tr>
<tr>
<td>4.2.7 Usage with limited manipulation or strength</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.7 and 302.8</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.7 and 302.8</td>
</tr>
<tr>
<td>4.2.8 Usage with limited reach</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.8</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.8</td>
</tr>
<tr>
<td>4.2.9 Minimize photosensitive seizure triggers</td>
<td>Supports</td>
<td>The pages of this product do not contain anything that flashes.</td>
</tr>
<tr>
<td>4.2.10 Usage with limited cognition</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.9</td>
<td>See <a href="#chapter-3-functional-performance-criteria-fpc">Revised Section 508 Report Ch.3</a> 302.9</td>
</tr>
<tr>
<td>4.2.11 Privacy</td>
<td>Supports</td>
<td>Standard HTML and WAI-ARIA attributes are used on these pages. The product does not impede the user from using their own privacy tools when interacting with the content.</td>
</tr>
</tbody>
</table>

### Clause [5: Generic Requirements](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=23)

Notes: This product supports standard web Assistive Technologies and is therefore not subject to the Closed Functionality criteria described in this chapter.

### Clause [6: ICT with Two-Way Voice Communication](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=30)

Notes: This product does not offer two-way voice communication and is therefore not subject to the requirements of this chapter.

### Clause [7: ICT with Video Capabilities](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=35)

Notes:

<table>
<thead>
<tr>
<th scope="col" id="chap-7-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-7-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-7-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<th scope="column" colspan="3" id="7-caption">7.1 Caption processing technology</th>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.1 Captioning playback</td>
<td headers="7-caption chap-7-conformance">Partially Supports</td>
<td headers="7-caption chap-7-remarks">Some but not all audio is supported by captions. Where captions are available, the user can choose whether or not to display them.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.2 Captioning synchronization</td>
<td headers="7-caption chap-7-conformance">Partially Supports</td>
<td headers="7-caption chap-7-remarks">Some but not all audio is supported by captions. Where captions are available, they are synchronised with the audio.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.1.3 Preservation of captioning</td>
<td headers="7-caption chap-7-conformance">Partially Supports</td>
<td headers="7-caption chap-7-remarks">Some but not all audio is supported by captions. Where captions are available, we do not override the appearance of the default caption display.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.1 Audio description playback</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Audio description is not generally used across our content.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.2 Audio description synchronization</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Audio description is not generally used across our content.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.2.3 Preservation of audio description</td>
<td headers="7-caption chap-7-conformance">Does Not Support</td>
<td headers="7-caption chap-7-remarks">Audio description is not generally used across our content.</td>
</tr>
<tr>
<td headers="7-caption chap-7-criteria">7.3 User controls for captions and audio description</td>
<td headers="7-caption chap-7-conformance">Partially Supports</td>
<td headers="7-caption chap-7-remarks">Audio description is not generally used across our content. Some but not all audio is supported by captions. Where captions are available, the mechanism for selecting them is presented at the same level as other playback controls.</td>
</tr>
</tbody>
</table>

### Clause [8: Hardware](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=37)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Clause [9: Web](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=45)

Notes: Please see [WCAG 2.2 section](#wcag-22-report).

### Clause [10: Non-Web Documents](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=52)

Notes: This product does not include non-web documents and is therefore not subject to the requirements of this chapter.

### Clause [11: Software](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=64)

<table>
<thead>
<tr>
<th scope="col" id="chap-11-criteria"><strong>Criteria</strong></th>
<th scope="col" id="chap-11-conformance"><strong>Conformance Level</strong></th>
<th scope="col" id="chap-11-remarks"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<th scope="column" colspan="3" id="11-gen">11.0 General (informative)</th>
</tr>
<td headers="11-gen chap-11-criteria">11.1.1 through 11.4.1.3</td>
<td headers "11-gen chap-11-conformance">See <a href="#wcag-21-report">WCAG section</a></td>
<td headers "11-gen chap-11-remarks">See information in WCAG section</td>
</tr>
<tr>
<th scope="column" colspan="3" id="11-interop">11.5 Interoperability with assistive technology</th>
</tr>
<tr>
<th scope="column" colspan="3" id="11-closed">11.5.1 Closed functionality</th>
</tr>
<tr>
<th scope="column" colspan="3" id="11-a11y-serv">11.5.2 Accessibility services</th>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.1 Platform accessibility service support for software that provides a user interface</td>
<td headers="11-a11y-serv chap-11-conformance">See 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.2 Platform accessibility service support for assistive technologies</td>
<td headers="11-a11y-serv chap-11-conformance">See 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.3 Use of accessibility services</td>
<td headers="11-a11y-serv chap-11-conformance">See information in 11.5.2.5 through 11.5.2.17</td>
<td headers="11-ally-serv chap-11-remarks">See information in 11.5.2.5 through 11.5.2.17</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.4 Assistive technology</td>
<td headers="11-a11y-serv chap-11-conformance">Not Applicable</td>
<td headers="11-ally-serv chap-11-remarks">This product is not an Assistive Technology.</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.5 Object information</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.1 and 502.3.2</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.1 and 502.3.2</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.6 Row, column, and headers</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.3</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.3</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.7 Values</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.4 and 502.3.5</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.4 and 502.3.5</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.8 Label relationships</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.6</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.6</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.9 Parent-child relationships</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.7</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.7</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.10 Text</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.8 and 502.3.9</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.8 and 502.3.9</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.11 List of available actions</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.10</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.10</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.12 Execution of available actions</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.11</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.11</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.13 Tracking of focus and selection attributes</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.12</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.12</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.14 Modification of focus and selection attributes</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.13</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.13</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.15 Change notification</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.14</td>
<td headers="11-ally-serv chap-11-remarks">See<a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.14</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.16 Modifications of states and properties</td>
<td headers="11-a11y-serv chap-11-conformance"><a ref="#chapter-5-software">See Revised Section 508 Report Ch.5</a> 502.3.14</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5</a> 502.3.14</td>
</tr>
<tr>
<td headers="11-a11y-serv chap-11-criteria">11.5.2.17 Modifications of values and text</td>
<td headers="11-a11y-serv chap-11-conformance">See <a ref="#chapter-5-software"> Revised Section 508 Report Ch.5</a> 502.3.5 and 502.3.9</td>
<td headers="11-ally-serv chap-11-remarks">See <a ref="#chapter-5-software">Revised Section 508 Report Ch.5 </a>502.3.5 and 502.3.9</td>
</tr>
<tr>
<th scope="column" colspan="3" id="11-doc-a11y">11.6 Documented accessibility usage</th>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.6.1 User control of accessibility features</td>
<td headers="11-doc-a11y chap-11-conformance">Not Applicable</td>
<td headers="11-doc-a11y chap-11-remarks">This product is not considered platform software as defined by EN 301 549 V1.1.2. See <a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=15">3.1 Definitions</a>.</td>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.6.2 No disruption of accessibility features</td>
<td headers="11-doc-a11y chap-11-conformance">Not Applicable</td>
<td headers="11-doc-a11y chap-11-remarks">This product is not considered platform software as defined by EN 301 549 V1.1.2. The product does not impede the user in using accessibility features provided by their operating system and Assistive Technologies.</td>
</tr>
<tr>
<td headers="11-doc-a11y chap-11-criteria">11.7 User preferences</td>
<td headers="11-doc-a11y chap-11-conformance">Supports</td>
<td headers="11-doc-a11y chap-11-remarks">The pages of this product use standard HTML and CSS attributes that may be overridden in user-supplied style sheets.</td>
</tr>
<tr>
<th scope="column" colspan="3" id="11-authoring">11.8 Authoring tools</th>
</tr>
<tr>
<th scope="column" colspan="3" id="11-content-tech">11.8.1 Content technology</th>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.2 Accessible content creation (if not authoring tool, enter “not applicable”)</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.3 Preservation of accessibility information in transformations</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.4 Repair assistance</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">This product is not used as an authoring tool.</td>
</tr>
<tr>
<td headers="11-content-tech chap-11-criteria">11.8.5 Templates</td>
<td headers="11-content-tech chap-11-conformance">Not Applicable</td>
<td headers="11-content-tech chap-11-remarks">This product is not used as an authoring tool.</td>
</tr>
</tbody>
</table>

### Clause [12: Documentation and Support Services](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=84)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

### Clause [13: ICT Providing Relay or Emergency Service Access](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf#page=86)

Notes: This product does not provide any relay services, or access for Emergency Services.

## Legal Disclaimer (Springer Nature)

This document is provided for information purposes only and the contents hereof are subject to change without notice. Springer Nature does not warrant that this document is error free, nor does it provide any other warranties or conditions, whether expressed orally or implied in law, including implied warranties and conditions of merchantability or fitness for a particular purpose. Springer Nature specifically disclaims any liability with respect to this document and no contractual obligations are formed either directly or indirectly by this document. Springer Nature further makes no representation concerning the ability of Assistive Technologies or other products to interoperate with Springer Nature products. This document addresses the named product(s) or platforms only.
