# Nature Accessibility Conformance Report

### **VPAT**&reg; **Version 2.2 – July 2018**

**Name of Product/Version**: Nature.com _(we do not version our software)_  
**Product Description**: 
Nature.com publishes peer-reviewed research, reviews and news across a number of journals. This report refers entirely to the accessibility of editorial, journal, and magazine content published at the top level domain of <a href="http://www.nature.com">www.nature.com</a>, including informational pages, and to content found at idp.nature.com and payment.nature.com (for account management and subscription and payment management respectively). Content located at <a href="http://www.nature.com/subjects">http://www.nature.com/subjects</a> is covered in a <a href="https://github.com/springernature/vpat/blob/master/nature-content-discovery.md">separate VPAT</a>.  
**Date**: 21st January 2019  
**Contact information**: accessibility@springernature.com  
**Evaluation Methods Used**: Conformance to the listed accessibility standards has been evaluated by Springer Nature using a combination of static analysis tools and manual testing with assistive technologies.  

## Applicable Standards/Guidelines

This report covers the degree of conformance for the following accessibility standard/guidelines:

<table cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td><strong>Standard/Guideline</strong></td>
<td nowrap><strong>Included In Report</strong></td>
</tr>
<tr>
<td>Web Content Accessibility Guidelines 2.0, at <a href="http://www.w3.org/TR/2008/REC-WCAG20-20081211/">http://www.w3.org/TR/2008/REC-WCAG20-20081211/</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines">Revised Section 508 standards</a> as published by the U.S. Access Board in the Federal Register on January 18, 2017<br><a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/corrections-to-the-ict-final-rule">Corrections to the ICT Final Rule</a> as published by the US Access Board in the Federal Register on January 22, 2018</td>
<td nowrap><strong>Yes</strong></td>
</tr>
<tr>
<td>EN 301 549 Accessibility requirements suitable for public procurement of ICT products and services in Europe, - V1.1.2 (2015-04) at <a href="http://mandate376.standards.eu/standard">http://mandate376.standards.eu/standard</a></td>
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
- **Not Evaluated**: The product has not been evaluated against the criterion. This can be used only in WCAG 2.0 Level AAA.

## WCAG 2.0 Report

Tables 1 and 2 also document conformance with:
- EN 301 549: Chapter 9 - Web, Chapter 10 - Non-Web documents, Section 11.2.1- Non-Web Software (excluding closed functionality), and Section 11.2.2 - Non-Web Software (closed functionality).
- Revised Section 508: Chapter 5 – 501.1 Scope, 504.2 Content Creation or Editing, and Chapter 6 – 602.3 Electronic Support Documentation.

**Note**: When reporting on conformance with the WCAG 2.0 Success Criteria, they are scoped for full pages, complete processes, and accessibility-supported ways of using technology as documented in the [WCAG 2.0 Conformance Requirements](https://www.w3.org/TR/WCAG20/#conformance-reqs).

### Table 1: Success Criteria, Level A

<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all"><strong>1.1.1 Non-text Content</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1 (Web)</li>
<li>10.2.1 (non-web document)</li>
<li>11.2.1.1 (Software)</li>
<li>11.2.2.1 (Closed Functionality Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
With rare exceptions, most images that we supply provide alternative text, or descriptions, or figure captions. We may use WAI-ARIA techniques to link some complex images with their descriptions if alternative text is unable to provide adequate context. We are working towards full support.  
<br><br>
Background images such as icons on user interface elements are generally identified with text labels. These may be visible, visually-hidden, or supplied using WAI-ARIA techniques.
<br><br>
We mark up some images so that they can be ignored by Assistive Technologies if they are <a href="https://www.w3.org/TR/WCAG21/#dfn-pure-decoration"><i>pure decoration</i></a> (as defined by WCAG 2.0).
<br><br>
The Nature subscription pages at <a href="https://www.nature.com/nature/subscribe">https://www.nature.com/nature/subscribe</a> currently contain SVG images without text alternatives, and decorative SVG images that are not marked up to be ignored by Assistive Technologies. We are actively working to repair these problems. 
<br><br>
Third party scripts may inject non-text content without text alternatives. These include images in advertising scripts, in Disqus commenting widgets, and in the "manage cookies" privacy centre. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2 (Web)</li>
<li>10.2.2 (non-web document)</li>
<li>11.2.1.2 (Software)</li>
<li>11.2.2.2.1 and 11.2.2.2.2 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
Nature.com has a diverse mix of multimedia content, both self-hosted and hosted on third party sites. Video-only content is generally used to support text-based content. 
<br><br>
Audio-only content may be used to support text-based content. Audio-only content may also be used in Podcasts across various journals. Some but not all podcasts provide transcripts. 
<br><br>
We currently have no method of confirming the inclusion - or not - of adequate media alternatives or transcripts. 	
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions"><strong>1.2.2 Captions (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.3 (Web)</li>
<li>10.2.3 (non-web document)</li>
<li>11.2.1.3 (Software)</li>
<li>11.2.2.3 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Nature.com has a diverse mix of multimedia content, both self-hosted and hosted on third party sites. Captions and/or transcripts may be provided for some pre-recorded content, but we currently have no method of confirming the inclusion - or not - of transcripts or captions. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4 (Web)</li>
<li>10.2.4 (non-web document)</li>
<li>11.2.1.4 (Software)</li>
<li>11.2.2.4 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
Nature.com has a diverse mix of multimedia content, both self-hosted and hosted on third party sites. Audio description is not generally used across our content, but some media may provide media alternatives such as text descriptions of video content. 
<br><br>
We currently have no method of confirming the inclusion - or not - of adequate media alternatives.
</td>
</tr>
<tr id="info-and-relationships">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic"><strong>1.3.1 Info and Relationships</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.7 (Web)</li>
<li>10.2.7 (non-web document)</li>
<li>11.2.1.7 (Software)</li>
<li>11.2.2.7 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The Nature subscription pages at <a href="https://www.nature.com/nature/subscribe">https://www.nature.com/nature/subscribe</a> currently contain sections of content marked up with inappropriate list and definition list semantics. They also contain elements that may be poorly-supported by client technology (<code>detail</code>), without using workarounds for the lack of support. We are actively working to repair these problems. 
<br><br>
Articles or supplementary pages ("about this journal", help pages etc.) may use unsemantic markup, including inadequate, misleading, or missing headings. We are actively working to find and repair these problems. 
<br><br>
Some parts of the checkout flow and the "My Account" pages contain unsemantic markup, including out-of-sequence headings and and incorrectly-applied landmarks. We are actively working to find and repair these problems. 
<br><br>
We make use of ARIA roles to support landmarks, and use ARIA roles and properties when required for more complex functionality such as popup menus and dialogs. 
<br><br>
Some complex functionality may omit required ARIA roles, states, or attributes, or abuse ARIA markup and techniques. We are actively working to find and repair these problems. 
<br><br>
Third party scripts may inject content with incorrect or absent information about structure and relationships. These include content in advertising scripts, in Disqus commenting widgets, and in the "manage cookies" privacy centre, among others.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence"><strong>1.3.2 Meaningful Sequence</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.8 (Web)</li>
<li>10.2.8 (non-web document)</li>
<li>11.2.1.8 (Software)</li>
<li>11.2.2.8 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The meaning of the content in the pages of Nature.com does not depend on the order of the sections.
<br><br>
We use semantically-correct markup to allow assistive technologies to interpret the meaning of content and controls within each section.
</td>
</tr>
<tr>
<td><strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding">1.3.3 Sensory Characteristics</a></strong> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.9 (Web)</li>
<li>10.2.9 (non-web document)</li>
<li>11.2.1.9 (Software)</li>
<li>11.2.2.9 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Icons may be displayed to control functionality, but adjacent visible text labels or aria-labels are also provided to ensure that relationships are available to Assistive Technologies.
<br><br>
Some complex images supplied by research authors may rely on sensory characteristics to be understood. Examples may include images of charts, graphs, or maps. Generally, these images are used to supplement text content. 
</td>
</tr>
<tr id="use-of-color">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color"><strong>1.4.1 Use of Color</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.10 (Web)</li>
<li>10.2.10 (non-web document)</li>
<li>11.2.1.10 (Software)</li>
<li>11.2.2.10 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Links and icons may use colour to indicate hover or active states. These are supplemented with visible focus rings and/or text decoration underlines and/or luminosity differences per WAI techniques <a href="https://www.w3.org/WAI/WCAG21/Techniques/general/G183">G183</a> and <a href="https://www.w3.org/WAI/WCAG21/Techniques/css/C15">C15</a>.
<br><br>
Some complex images supplied by research authors may rely on colour as the only visual means of understanding information. Examples may include images of charts, graphs, or maps. Generally, these images are used to supplement text content. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio"><strong>1.4.2 Audio Control</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.11 (Web)</li>
<li>10.2.11 (non-web document)</li>
<li>11.2.1.11 (Software)</li>
<li>11.2.2.11 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Content supplied by us does not play automatically. All audio files supplied by us, either hosted on our own platform or through a third party, has mechanisms for pausing, stopping, and controlling volume. 
<br><br>
Third party advertisements may load video and audio that automatically starts, and may not provide adequate controls for pausing, stopping, and/or controlling volume. When we become aware of active advertisements with these problems, we immediately take steps to remove those advertisements from our pages.
</td>
</tr>
<tr id="keyboard">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable"><strong>2.1.1 Keyboard</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.15 (Web)</li>
<li>10.2.15 (non-web document)</li>
<li>11.2.1.15 (Software)</li>
<li>11.2.2.15 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
The majority of components in Nature.com can be navigated by keyboard alone. Complex elements like flyout menus can be exited with the <kbd>esc</kbd> key. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Third party advertising scripts may inject content that can't be interacted with easily or at all by keyboard.
<br><br>
The "manage cookies" privacy centre banner (third party content) cannot be interacted with easily by keyboard alone. An alternative static link to the privacy centre is provided in the footer of each page.
<br><br>
Other types of third party content such as JavaScript-based file viewers, commenting systems, or customer services widgets may be difficult to use with keyboard alone. Where we know of deficiencies, we have contacted third party suppliers to request repairs. Additionally, where possible, we aim to provide equivalent alternatives to problematic content. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping"><strong>2.1.2 No Keyboard Trap</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.16 (Web)</li>
<li>10.2.16 (non-web document)</li>
<li>11.2.1.16 (Software)</li>
<li>11.2.2.16 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Keyboard trapping inside components on Nature.com pages is fairly rare, and in most cases should be managed appropriately, allowing focus to be moved away from any component using standard keystrokes (<kbd>tab</kbd>, <kbd>shift</kbd>, <kbd>esc</kbd>). 
<br><br>
Third party content such as modal dialogs or the Disqus commenting widget may trap focus and provide inadequate methods of escaping. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors"><strong>2.2.1 Timing Adjustable</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.17 (Web)</li>
<li>10.2.17 (non-web document)</li>
<li>11.2.1.17 (Software)</li>
<li>11.2.2.17 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-pause"><strong>2.2.2 Pause, Stop, Hide</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.18 (Web)</li>
<li>10.2.18 (non-web document)</li>
<li>11.2.1.18 (Software)</li>
<li>11.2.2.18 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Any moving, blinking or scrolling content on Nature.com generally does not start automatically, and is complemented by controls that allow users to pause or otherwise stop the content. Moving images in the form of gifs may not meet this criteria. 
<br><br>
Automatically updating information is rare on Nature.com. The Disqus commenting widget may update new comments on screen automatically. If users are actively interacting with the widget, then new comments may be progressively disclosed to users at their request by activating a "load new comments" button. 
<br><br>
Third party advertising scripts may inject content that automatically moves or blinks and lasts more than five seconds, without providing a mechanism to pause, stop, or hide that content. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate"><strong>2.3.1 Three Flashes or Below Threshold</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.19 (Web)</li>
<li>10.2.19 (non-web document)</li>
<li>11.2.1.19 (Software)</li>
<li>11.2.2.19 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip"><strong>2.4.1 Bypass Blocks</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.20 (Web)</li>
<li>10.2.20 (non-web document) – Does not apply</li>
<li>11.2.1.20 (Software) – Does not apply</li>
<li>11.2.2.20 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
We use semantically-correct markup so that Assistive Technology users can recognise elements and move around them accordingly. We make use of ARIA roles to support landmarks. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
The "manage cookies" privacy centre (third party content) does not provide a way for screen reader users to bypass the links in its left hand menu.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title"><strong>2.4.2 Page Titled</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.21 (Web)</li>
<li>10.2.21 (non-web document)</li>
<li>11.2.1.21 (Software) - Does not apply</li>
<li>11.2.2.21 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Most of the pages on Nature.com have unique page titles that describe the purpose of the page. 
<br><br>
Some pages (e.g in checkout flows) do not have unique page titles at every stage in a process. We are actively working to find and repair these problems. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order"><strong>2.4.3 Focus Order</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.22 (Web)</li>
<li>10.2.22 (non-web document)</li>
<li>11.2.1.22 (Software)</li>
<li>11.2.2.22 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The meaning or operation of the pages on Nature.com is generally unaffected by focus order. The focus order of all page content matches the visual order.
<br><br>
Third party scripts including advertising scripts, the Disqus commenting widget, or survey or customer services widgets (among others), may inject content where the focus order does not match the visual order. The operation and meaning of these components should be unaffected by the focus order. 
</td>
</tr>
<tr id="link-purpose-in-context">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs"><strong>2.4.4 Link Purpose (In Context)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.23 (Web)</li>
<li>10.2.23 (non-web document)</li>
<li>11.2.1.23 (Software)</li>
<li>11.2.2.23 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Generally, the purpose of each link that we provide can be determined by its descriptive text label; linked images or icons have alternative text or similar to provide this context. 
<br><br>
In research articles, anchor links that refer to same-page supplementary figures or tables may have insufficient context in their link text. Repetitive links (e.g. "show more" or "view all" type links in lists of content) may not be differentiated from each other. In limited cases we may support poor link text with the use of ARIA labels. We are actively working to repair these problems. 
<br><br>
Third party scripts including advertising scripts, the Disqus commenting widget, or survey or customer services widgets (among others), may inject content that includes links with no accessible text, or poorly-named accessible text. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
<br><br>
The "manage cookies" privacy centre (third party content) displays some links with a title attribute instead of accessible text; the title attribute may not be made available by all Assistive Technologies.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id"><strong>3.1.1 Language of Page</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.27 (Web)</li>
<li>10.2.27 (non-web document)</li>
<li>11.2.1.27 (Software)</li>
<li>11.2.2.27 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
The majority of the pages in this product use the language attribute on the HTML element to specify the default language of a page. Some (e.g some pages in checkout flows) do not. We are actively working to repair these problems. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus"><strong>3.2.1 On Focus</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.29 (Web)</li>
<li>10.2.29 (non-web document)</li>
<li>11.2.1.29 (Software)</li>
<li>11.2.2.29 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td>Components in the interface of the pages of this product that receive focus do not initiate a change of context.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change"><strong>3.2.2 On Input</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.30 (Web)</li>
<li>10.2.30 (non-web document)</li>
<li>11.2.1.30 (Software)</li>
<li>11.2.2.30 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td>Changing the setting of any user interface component does not automatically cause a change of context on any of the pages of this product.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-identified"><strong>3.3.1 Error Identification</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.33 (Web)</li>
<li>10.2.33 (non-web document)</li>
<li>11.2.1.33 (Software)</li>
<li>11.2.2.33 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
Where user input errors are automatically detected in our own software, the items that are in error are identified to the user with warning text adjacent to the input field. We do not rely on visual characteristics alone (e.g. colour) to indicate user input errors. 
<br><br>
Third party scripts including the Disqus commenting widget, or other widgets that accept user input, may automatically detect errors but fail to present the errors to users in text. They may rely on visual characteristics alone to indicate user input errors, or place error text in locations that are difficult for screen reader users to access. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
<tr id="labels-or-instructions">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues"><strong>3.3.2 Labels or Instructions</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.34 (Web)</li>
<li>10.2.34 (non-web document)</li>
<li>11.2.1.34 (Software)</li>
<li>11.2.2.34 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Generally, visible and appropriately associated labels are provided for input fields. In some cases, a visually-hidden label may be provided instead (e.g. the main search component in the page banner). 
<br><br>
Instructions such as those that explain mandatory fields may be absent or only present at the end of forms. (e.g. some payment information pages). Instructions for specific input fields may not be adequately associated (e.g. with ARIA) with the fields they describe. We are actively working to find and repair these problems. 
<br><br>
In rare cases, input fields may use only placeholder text as instruction, without associated labels or ARIA descriptions. We are actively working to find and repair these problems. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses"><strong>4.1.1 Parsing</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.37 (Web)</li>
<li>10.2.37 (non-web document)</li>
<li>11.2.1.37 (Software)</li>
<li>11.2.2.37 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The pages of this product generally use semantically-correct markup that meets the HTML5 specification for interface elements.
<br><br>
Nature magazine and a limited number of journals publish editorial content from a content management system (CMS). Some journals may contain older editorial content hand-built in HTML, without the use of a dynamic templating system. Hand-built content or content generated by CMS may contain unclosed or illegally nested elements. When we become aware of content with these problems, we immediately take steps to repair the HTML.
<br><br>
Third party advertising scripts may inject content that omits start and end tags, contains duplicate attributes or contains illegally nested elements. When we become aware of active advertisements with these problems, we immediately take steps to remove those advertisements from our pages.
</td>
</tr>
<tr id="name-role-value">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv"><strong>4.1.2 Name, Role, Value</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.38 (Web)</li>
<li>10.2.38 (non-web document)</li>
<li>11.2.1.38 (Software)</li>
<li>11.2.2.38 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
In some cases, ARIA attributes have been omitted where they are required when client user agent support for a standard HTML5 feature is poor (e.g. in the "for individuals/post docs/students" disclosure area on subscription pages). In other cases ARIA roles or attributes may be misused in ways that cause elements to have misleading semantics. We are actively working to find and repair these problems. 
<br><br>
The "manage cookies" privacy centre (third party content) uses an inappropriate aria label of "true" in place of its main heading, and both links and images exist with no accessible name. Additionally, when a screenreader user activates a link on the left hand menu of the Privacy Preference Centre, they are not made aware that the content on the right has updated. We have reported these problems to the vendor. 
<br><br>
Other third party scripts, including the Disqus commenting widget, may present interactive elements such as tooltips that lack adequate names and roles, making them difficult for screen reader users to access. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
</tbody>
</table>

### Table 2: Success Criteria, Level AA

<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions"><strong>1.2.4 Captions (Live)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5 (Web)</li>
<li>10.2.5 (non-web document)</li>
<li>11.2.1.5 (Software)</li>
<li>11.2.2.5 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only"><strong>1.2.5 Audio Description (Prerecorded)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.6 (Web)</li>
<li>10.2.6 (non-web document)</li>
<li>11.2.1.6 (Software)</li>
<li>11.2.2.6 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td>We do not generally provide audio description for prerecorded video. A limited form of audio description may be provided for some pre-recorded content, but we currently have no method of confirming the inclusion - or not - of audio description. </td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast"><strong>1.4.3 Contrast (Minimum)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.12 (Web)</li>
<li>10.2.12 (non-web document)</li>
<li>11.2.1.12 (Software)</li>
<li>11.2.2.12 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
All text and images of text supplied by us on the pages of this product have a contrast ratio of at least 4.5:1.
<br><br>
Third party advertising scripts may inject content with insufficient contrast.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale"><strong>1.4.4 Resize text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.13 (Web)</li>
<li>10.2.13 (non-web document)</li>
<li>11.2.1.13 (Software)</li>
<li>11.2.2.13 (Closed Software)</li>
<li>11.6.2 (Authoring Tool)</li>
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
All text on the pages of this product supplied by us can be resized up to 400% without loss of information or functionality.
<br><br>
Third party advertising scripts may inject non-responsive content that loses or obscures information when text is resized.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation"><strong>1.4.5 Images of Text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.14 (Web)</li>
<li>10.2.14 (non-web document)</li>
<li>11.2.1.14 (Software)</li>
<li>11.2.2.14 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Editorial content and published papers may include complex images that contain images of text. In most cases these images are used to supplement the text content they appear alongside. In some cases (e.g. charts, graphs, or maps, among others), the text content presented alongside may be insufficient to explain the contents of the image. 
<br><br>
Third party advertising scripts may inject images containing images of text.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc"><strong>2.4.5 Multiple Ways</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.24 (Web)</li>
<li>10.2.24 (non-web document) – Does not apply</li>
<li>11.2.1.24 (Software) – Does not apply</li>
<li>11.2.2.24 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<tr id="headings-and-labels">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive"><strong>2.4.6 Headings and Labels</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.25 (Web)</li>
<li>10.2.25 (non-web document)</li>
<li>11.2.1.25 (Software)</li>
<li>11.2.2.25 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Our document structure is semantically marked up using headings to create a sequential hierarchy of content. Sometimes headings or labels may be visually hidden but available to Assistive Technologies.
<br><br>
Nature magazine and a limited number of journals publish editorial content from a content management system (CMS). Content generated by CMS may lack appropriate headings (e.g. using bold text as implicit headings instead of semantically-marked up heading elements). 
<br><br>
Some parts of the product (e.g. some payment and "my account" pages) use inappropriate heading levels for visual effect. We are actively working to repair these problems. 
<br><br>
The "manage cookies" privacy centre (third party content) uses an inappropriate aria label of "true" in place of its main heading. We have reported this problem to the vendor.
<br><br>
Other third party scripts, including survey or customer services widgets, may inject content with inadequate or inappropriate headings or labels. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
<tr id="focus-visible">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible"><strong>2.4.7 Focus Visible</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.26 (Web)</li>
<li>10.2.26 (non-web document)</li>
<li>11.2.1.26 (Software)</li>
<li>11.2.2.26 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Some pages (e.g. some payment or "my account" pages) use default focus rings only. In some of these pages, the default focus ring has been removed from input elements and replaced with a different focus style that provides inadequate visibility. We are actively working to repair these problems; the high-visibility focus ring across the majority of Nature.com is intended to be the default. 
<br><br>
Pages that use older designs may use default focus rings only. We are in the process of transferring all content from the older designs to the design currently used across the majority of Nature.com; when this process is complete, the high-visibility focus ring will be the default. 
<br><br>
Third party scripts, including advertising, may inject components that remove focus styles.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id"><strong>3.1.2 Language of Parts</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.28 (Web)</li>
<li>10.2.28 (non-web document)</li>
<li>11.2.1.28 (Software) – Does not apply</li>
<li>11.2.2.28 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td>All components on the pages of this product supplied by us as part of dynamic templates use the same language defined in the HTML <code>lang</code> attribute, therefore Language of Parts is not applicable for the majority of this product.
<br><br>
Editorial content or published papers may include text in languages other than that defined in the HTML <code>lang</code> attribute. We currently have no method of confirming the inclusion - or not - of appropriate lang attributes for pieces of text that may use a different language to the main document. 
<br><br>
Third party scripts may inject components that use a different language to the page content - for example a targeted advertisment or file presented in a file viewer may use the native language of the user. These may not be marked up with a separate <code>lang</code> attribute.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations"><strong>3.2.3 Consistent Navigation</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.31 (Web)</li>
<li>10.2.31 (non-web document) – Does not apply</li>
<li>11.2.1.31 (Software) – Does not apply</li>
<li>11.2.2.31 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The Nature.com website contains content that is rendered in a number of different, inconsistent designs. The designs often have dramatically different navigation methods, within the same collections of pages. Supplementary content, such as informational pages adjunct to journal and editorial content, is more likely to be affected. 
<br><br>
We are in the process of transferring all content from the older designs to the design currently used across the majority of Nature.com; when this process is complete, the navigation methods will be broadly consistent. 
<br><br>
Pages that deal with sensitive information (including payment pages and "my account" pages) have an intentionally stripped-down design, and do not share the same navigation system as the main site. The navigation of each of these sets of pages is internally consistent. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality"><strong>3.2.4 Consistent Identification</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.32 (Web)</li>
<li>10.2.32 (non-web document) – Does not apply</li>
<li>11.2.1.32 (Software) – Does not apply</li>
<li>11.2.2.32 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
The Nature.com website contains content that is rendered in a number of different, inconsistent designs, within the same collections of pages. Supplementary content, such as informational pages adjunct to journal and editorial content, is more likely to be affected. 
<br><br>
We are in the process of transferring all content from the older designs to the design currently used across the majority of Nature.com; when this process is complete, all editorial, supplementary, and journal content will use a unified design style with consistent presentation and functionality.
<br><br>
Pages that deal with sensitive information (including payment pages and "my account" pages) have an intentionally stripped-down design. The presentation of each of these sets of pages is internally consistent, and the tasks performed are unlike those performed elsewhere on the site. 
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions"><strong>3.3.3 Error Suggestion</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.35 (Web)</li>
<li>10.2.35 (non-web document)</li>
<li>11.2.1.35 (Software)</li>
<li>11.2.2.35 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
Where user input errors are automatically detected in our own software, the items that are in error are identified to the user with warning text adjacent to the input field. Unless it would present a risk to security, the warning text describes the error and what the user should do to correct it. 
<br><br>
Third party scripts including the Disqus commenting widget, or other widgets that accept user input, may automatically detect errors but fail to present the errors to users in ways that they can perceive. They may rely on visual characteristics alone to indicate user input errors, or place error text in locations that are difficult for screen reader users to access. Where we know of deficiencies, we have contacted third party suppliers to request repairs.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.36 (Web)</li>
<li>10.2.36 (non-web document)</li>
<li>11.2.1.36 (Software)</li>
<li>11.2.2.36 (Closed Software) – Does not apply</li>
<li>11.6.2 (Authoring Tool)</li>
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
<td>Payment pages have a checkout flow that include a verification step. There, the user must confirm that their choices are correct before they may enter their payment details. At this stage they may return to a previous step to make corrections, cancel, or abandon the process.</td>
</tr>
</tbody>
</table>

### Table 3: Success Criteria, Level AAA

Notes: This product has not been evaluated for WCAG 2.0 Level AAA conformance.

## Revised Section 508 Report

### Chapter 3: [Functional Performance Criteria](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-3-functional-performance-criteria) (FPC)

| **Criteria**                                                   | **Conformance Level**    | **Remarks and Explanations** |
| -------------------------------------------------------------- | ---------------------    | ---------------------------- |
| 302.1 Without Vision                                           | Partially Supports       | The majority of content is marked up for Assistive Technology. Third party scripts may inject content with inadequate accessible alternatives. |
| 302.2 With Limited Vision                                      | Partially Supports	    | Markup is written with support for assistive technology. Text is resizable by the user. Fonts are set as rems and use pixels as a fallback if not supported. The product does not impede the user from zooming into page. Third party scripts may inject content with inadequate accessibility support. |
| 302.3 Without Perception of Color                              | Supports                 | Color perception is not needed to use this product. |
| 302.4 Without Hearing                                          | Partially Supports       | Some but not all audio is supported by captions or transcripts.  |
| 302.5 With Limited Hearing                                     | Partially Supports       | Some but not all audio is supported by captions or transcripts.  |
| 302.6 Without Speech                                           | Not Applicable	        | Speech is not needed to use this product. |
| 302.7 With Limited Manipulation                                | Partially Supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Fine motor control and simultaneous actions are not required to operate this product. Third party scripts may inject content that is difficult to use without a pointing device. |
| 302.8 With Limited Reach and Strength                          | Partially Supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Third party scripts may inject content that is difficult to use without a pointing device. |
| 302.9 With Limited Language, Cognitive, and Learning Abilities | Partially Supports       | The pages of this product generally have a consistent presentation with clear labels, titles, and accessible names for controls. Third party scripts may inject content with inconsistent or absent labelling of interface components. |

### Chapter 4: [Hardware](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-4-hardware)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter 5: [Software](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-5-platforms-and-applications)

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
<td>501.1 Scope – Incorporation of WCAG 2.0 AA</td>
<td>See <a href="#WCAG">WCAG 2.0</a> section</td>
<td>See information in WCAG section</td>
</tr>
<tr>
<td><em><strong>502 Interoperability with Assistive Technology</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>502.2.1 User Control of Accessibility Features</td>
<td>Not Applicable</td>
<td>This product is not considered platform software as defined by Section 508. See <a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines#E103-definitions">E103 Definitions, section E103.4</a>.</td>
</tr>
<tr>
<td>502.2.2 No Disruption of Accessibility Features</td>
<td>Not Applicable</td>
<td>
This product has no platform features as defined by Section 508. The product is compatible with operating system and browser accessibility features configured by the user.
<br><br>
Third party scripts may inject content that disrupts standard operating system and browser accessibility features. See information in WCAG section for complete details.
</td>
</tr>
<tr>
<td><em><strong>502.3 Accessibility Services</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>502.3.1 Object Information</td>
<td>Partially Supports</td>
<td>
Object role, state(s), properties, boundary, name, and description are generally programmatically determinable.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.2 Modification of Object Information</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML or ARIA object roles for maximum compatibility with assistive technologies.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.3 Row, Column, and Headers</td>
<td>Partially Supports</td>
<td>
Data tables in original research or editorial content may not be marked up with adequate table header information.
<br><br>
Data tables in dynamic templates are rare, but where they do appear, they are marked up with standard HTML table elements. Row headers are present and associated with rows and columns as necessary.
</td>
</tr>
<tr>
<td>502.3.4 Values</td>
<td>Supports</td>
<td>The pages of this product use standard HTML or ARIA object attributes for maximum compatibility with assistive technologies.</td>
</tr>
<tr>
<td>502.3.5 Modification of Values</td>
<td>Supports</td>
<td>The pages of this product use standard HTML or ARIA object attributes for maximum compatibility with assistive technologies.</td>
</tr>
<tr>
<td>502.3.6 Label Relationships</td>
<td>Partially Supports</td>
<td>
Generally, the pages in this product use labels on components that require user input. Some exceptions exist. 
<br><br>
See WCAG sections <a href="#headings-and-labels">2.4.6 Headings and Labels</a> and <a href="#labels-or-instructions">3.3.2 Labels or Instructions</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.7 Hierarchical Relationships</td>
<td>Partially Supports</td>
<td>
The pages of this product generally use standard HTML to express hierarchy. Third party scripts may inject content that obscures the relationships between components.
<br><br>
See WCAG section <a href="#info-and-relationships">1.3.1 Info and Relationships</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.8 Text</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard plain text in HTML.
<br><br>
The "manage cookies" privacy centre (Third party content) uses an inappropriate aria label of "true" in place of its main heading. Some text in the privacy center (e.g. link text) may be present only in a title attribute, and may not be accessible to some assistive technologies.
<br><br>
Original research or editorial content may contain images of text without adequate programmatically determinable alternatives. 
</td>
</tr>
<tr>
<td>502.3.9 Modification of Text</td>
<td>Supports</td>
<td>The pages of this product use standard HTML for user input.</td>
</tr>
<tr>
<td>502.3.10 List of Actions</td>
<td>Supports</td>
<td>The pages of this product use standard HTML or ARIA object attributes for maximum compatibility with assistive technologies.</td>
</tr>
<tr>
<td>502.3.11 Actions on Objects</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML or ARIA object attributes for maximum compatibility with assistive technologies.
<br><br>
Some third party scripts may inject content that can't be interacted with easily or at all by keyboard or by some assistive technologies.
<br><br>
See WCAG section <a href="#keyboard">2.1.1 Keyboard</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.12 Focus Cursor</td>
<td>Partially Supports</td>
<td>
We provide focus styles on all focusable elements. Third party scripts may inject components that remove focus styles or alter focus in a way that makes them difficult to perceive by all users.
<br><br>
See WCAG sections <a href="#use-of-color">1.4.1 Use of Color</a> and <a href="#focus-visible">2.4.7 Focus Visible</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.13 Modification of Focus Cursor</td>
<td>Supports</td>
<td>The pages of this product use standard HTML elements and cursor controls for user input that may be overriden by assistive technology.</td>
</tr>
<tr>
<td>502.3.14 Event Notification</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
Rarely, components may omit or misuse WAI-ARIA attributes in a way that prevents users of some Assistive Technologies from being able to percieve changes in state. We are actively working to find and repair these problems. 
<br><br>
Some third party scripts may inject content that fails to notify users of changes in state.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a> and <a href="#name-role-value">4.1.2 Name, Role, Value</a> for further detail.
</td>
</tr>
<tr>
<td>502.4 Platform Accessibility Features</td>
<td>Not Applicable</td>
<td>This product is not considered platform software as defined by Section 508. See <a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines#E103-definitions">E103 Definitions, section E103.4</a>.</td>
</tr>
<tr>
<td><em><strong>503 Applications</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>503.2 User Preferences</td>
<td>Supports</td>
<td>This product does not override user selected contrast and color selections and other individual display attributes.</td>
</tr>
<tr>
<td>503.3 Alternative User Interfaces</td>
<td>Not Applicable</td>
<td>We do not provide any alternative user interface for this product that functions as assistive technology.</td>
</tr>
<tr>
<td><em><strong>503.4 User Controls for Captions and Audio Description</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>503.4.1 Caption Controls</td>
<td>Partially Supports</td>
<td>Not all video content provides captions. Where captions are provided, the controls for adjusting those captions are found at the same menu level as the user controls for volume or program selection.</td>
</tr>
<tr>
<td>503.4.2 Audio Description Controls</td>
<td>Does Not Support</td>
<td>Audio description is not generally used across our content.</td>
</tr>
<tr>
<td><em><strong>504 Authoring Tools</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>504.2 Content Creation or Editing (if not authoring tool, enter “not applicable”)</td>
<td>Not Applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
<tr>
<td>504.2.1 Preservation of Information Provided for Accessibility in Format Conversion</td>
<td>Not Applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
<tr>
<td>504.2.2 PDF Export</td>
<td>Not Applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
<tr>
<td>504.3 Prompts</td>
<td>Not Applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
<tr>
<td>504.4 Templates</td>
<td>Not Applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
</tbody>
</table>

### Chapter 6: [Support Documentation and Services](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-6-documentation-and-support-services)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

## EN 301 549 Report

### Chapter 4: [4.2 Functional Performance Statements](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=22) (FPS)

| **Criteria**                                      | **Conformance Level**                                                                       | **Remarks and Explanations**                                                                |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------  | ------------------------------------------------------------------------------------------- |
| 4.2.1 Usage without vision                        | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.1 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.1 |
| 4.2.2 Usage with limited vision                   | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.2 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.2 |
| 4.2.3 Usage without perception of colour          | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.3 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.3 |
| 4.2.4 Usage without hearing                       | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.4 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.4 |
| 4.2.5 Usage with limited hearing                  | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.5 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.5 |
| 4.2.6 Usage without vocal capability              | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.6 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.6 |
| 4.2.7 Usage with limited manipulation or strength | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.7 and 302.8 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.7 and 302.8 |
| 4.2.8 Usage with limited reach                    | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.8 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.8 |
| 4.2.9 Minimize photosensitive seizure triggers    | Supports                                                                         | The pages of this product do not contain anything that flashes.                             |
| 4.2.10 Usage with limited cognition               | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.9 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.9 |
| 4.2.11 Privacy                                    | Supports                                                                         | Standard HTML and WAI-ARIA attributes are used on these pages. The product does not impede the user from using their own privacy tools when interacting with the content. |

### Chapter [5: Generic Requirements](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=23)

Notes: This product supports standard web assistive technologies and is therefore not subject to the Closed Functionality criteria described in this chapter.

### Chapter [6: ICT with Two-Way Voice Communication](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=28) 

Notes: This product does not offer two-way voice communication and is therefore not subject to the requirements of this chapter.

### Chapter [7: ICT with Video Capabilities](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=31) 

Notes:

| **Criteria**                                         | **Conformance Level**               | **Remarks and Explanations**        |
| ---------------------------------------------------- | ----------------------------------- | ----------------------------------- |
| ***7.1 Caption processing technology***              | -                                   | -                                   |
| 7.1.1 Captioning playback                            | Partially Supports                  | Some but not all audio is supported by captions. Where captions are available, the user can choose whether or not to display them. |
| 7.1.2 Captioning synchronization                     | Partially Supports                  | Some but not all audio is supported by captions. Where captions are available, they are synchronised with the audio. |
| 7.1.3 Preservation of captioning                     | Partially Supports                  | Some but not all audio is supported by captions. Where captions are available, we do not override the appearance of the default caption display. |
| 7.2.1 Audio description playback                     | Does Not Support                    | Audio description is not generally used across our content. |
| 7.2.2 Audio description synchronization              | Does Not Support                    | Audio description is not generally used across our content. |
| 7.2.3 Preservation of audio description              | Does Not Support                    | Audio description is not generally used across our content. |
| 7.3 User controls for captions and audio description | Partially Supports                  | Audio description is not generally used across our content. Some but not all audio is supported by captions. Where captions are available, the mechanism for selecting them is presented at the same level as other playback controls. |

### Chapter [8: Hardware](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=32)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter [9: Web](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=39)

Notes: Please see [WCAG 2.0 section](#wcag-2.0-report).

### Chapter [10: Non-web Documents](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=43)

Notes: This product does not include non-web documents and is therefore not subject to the requirements of this chapter.

### Chapter [11: Software](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=53)

| **Criteria**                                                                                      | **Conformance Level**                                                                    | **Remarks and Explanations**                                                   |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 11.2.1 Software success criteria (excluding closed functionality)                                 | See [WCAG 2.0](#WCAG) section                                                            | See information in WCAG section                                                |
| 11.2.2 Software success criteria (closed functionality)                                           | See [WCAG 2.0](#WCAG) section                                                            | See information in WCAG section                                                |
| ***11.3 Interoperability with assistive technology***                                             | -                                                                                        | -                                                                              |
| ***11.3.1 Closed functionality (informative)***                                                   | -                                                                                        | -                                                                              |
| ***11.3.2 Accessibility services***                                                               | -                                                                                        | -                                                                              |
| ***11.3.2.1 Platform accessibility service support for software that provides a user interface*** | See 11.3.2.5 through 11.3.2.17                                                           | See information in 11.3.2.5 through 11.3.2.17                                  |
| ***11.3.2.2 Platform accessibility service support for assistive technologies***                  | See 11.3.2.5 through 11.3.2.17                                                           | See information in 11.3.2.5 through 11.3.2.17                                  |
| 11.3.2.3 Use of accessibility services                                                            | Supports                                                                                 | This product supports standard platform accessibility services.                |
| 11.3.2.4 Assistive technology                                                                     | Not Applicable                                                                           | This product is not an assistive technology.                                   |
| 11.3.2.5 Object information                                                                       | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.1 and 502.3.2 |
| 11.3.2.6 Row, column, and headers                                                                 | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.3             |
| 11.3.2.7 Values                                                                                   | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.4 and 502.3.5 |
| 11.3.2.8 Label relationships                                                                      | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.6             |
| 11.3.2.9 Parent-child relationships                                                               | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.7             |
| 11.3.2.10 Text                                                                                    | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.8 and 502.3.9 |
| 11.3.2.11 List of available actions                                                               | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.10            |
| 11.3.2.12 Execution of available actions                                                          | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.11            |
| 11.3.2.13 Tracking of focus and selection attributes                                              | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.12            |
| 11.3.2.14 Modification of focus and selection attributes                                          | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.13            |
| 11.3.2.15 Change notification                                                                     | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14            |
| 11.3.2.16 Modifications of states and properties                                                  | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14            |
| 11.3.2.17 Modifications of values and text                                                        | See [Revised Section 508 Report](#chapter-5-software)                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.5 and 502.3.9 |
| ***11.4 Documented accessibility usage***                                                         | -                                                                                        | -                                                                              |
| 11.4.1 User control of accessibility features                                                     | Not Applicable                                                                           | This product is not considered platform software as defined by EN 301 549 V1.1.2. See [3.1 Definitions](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=18). |
| 11.4.2 No disruption of accessibility features                                                    | Not Applicable                                                                           | This product is not considered platform software as defined by EN 301 549 V1.1.2. The product does not impede the user in using accessibility features provided by their operating system and Assistive Technologies. |
| 11.5 User preferences                                                                             | Supports                                                                                 | The pages of this product use standard HTML and CSS attributes that may be overridden in user-supplied style sheets. |
| ***11.6 Authoring tools***                                                                        | -                                                                                        | -                                                                              |
| ***11.6.1 Content technology***                                                                   | -                                                                                        | -                                                                              |
| 11.6.2 Accessible content creation (if not authoring tool, enter “not applicable”)                | Not Applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.3 Preservation of accessibility information in transformations                               | Not Applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.4 Repair assistance                                                                          | Not Applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.5 Templates                                                                                  | Not Applicable                                                                           | This product is not used as an authoring tool.                                 |

### Chapter [12: Documentation and Support Services](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=73)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

### Chapter [13: ICT Providing Relay or Emergency Service Access](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=74)

Notes: This product does not provide any relay services, or access for Emergency Services.

## Legal Disclaimer (Springer Nature)

This document is provided for information purposes only and the contents hereof are subject to change without notice. Springer Nature does not warrant that this document is error free, nor does it provide any other warranties or conditions, whether expressed orally or implied in law, including implied warranties and conditions of merchantability or fitness for a particular purpose. Springer Nature specifically disclaims any liability with respect to this document and no contractual obligations are formed either directly or indirectly by this document. Springer Nature further makes no representation concerning the ability of assistive technologies or other products to interoperate with Springer Nature products. This document addresses the named product(s) or platforms only.
