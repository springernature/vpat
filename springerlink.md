# SpringerLink Accessibility Conformance Report International Edition 
(Based on VPAT® Version 2.4)

**Report Date**: 10th June 2021  
**Name of Product/Version**: SpringerLink _(we do not version our software)_  
**Product Description**: SpringerLink provides researchers with access to scientific documents from journals, books, series, protocols, reference works and proceedings. This report refers entirely to the accessibility of all web documents published at the subdomains link.springer.com and rd.springer.com (both subdomains are referred to as link.springer.com throughout this report), including informational pages, and all web documents found at checkout.springer.com and order.springer.com.  
 **Contact information**: Please contact your Institutional Sales representative.   
 **Notes**:   
**Evaluation Methods Used**: Conformance to the listed accessibility standards has been evaluated by Springer Nature's dedicated Accessibility Specialists. We use a combination of static analysis tools (including but not limited to Axe, WAVE, and all of the tools described in our [Frontend Playbook's Accessibility Guide](https://github.com/springernature/frontend-playbook/blob/main/accessibility/tools.md)). Additionally, we perform manual testing (also described in our Frontend Playbook under the "Manual testing" and "Assistive technology" sections).  

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
<td>Web Content Accessibility Guidelines 2.1, at <a href="https://www.w3.org/TR/WCAG21">https://www.w3.org/TR/WCAG21</a></td>
<td nowrap>Level A &nbsp; – &nbsp; <strong>Yes</strong><br>Level AA &nbsp; – &nbsp; <strong>Yes</strong><br>Level AAA &nbsp; – &nbsp; <strong>No</strong></td>
</tr>
<tr>
<td><a href="https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines">Revised Section 508 standards</a> published January 18, 2017 and corrected January 22, 2018 </td>
<td nowrap><strong>Yes</strong></td>
</tr>
<tr>
<td>EN 301 549 Accessibility requirements suitable for public procurement of ICT products and services in Europe, - V3.1.1 (2019-11) at <a href="https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.01.01_60/en_301549v030101p.pdf">https://www.etsi.org/[...]/en_301549v030101p.pdf</a></td>
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
- **Not Evaluated**: The product has not been evaluated against the criterion. This can be used only in WCAG 2.1 Level AAA.

## WCAG 2.1 Report

Tables 1 and 2 also document conformance with:
- EN 301 549:  Chapter 9 - Web, Sections 10.1-10.4 of Chapter 10 - Non-Web documents, and Sections 11.1-11.4 and 11.8.2 of Chapter 11 - Non-Web Software (open and closed functionality), and Sections 12.1.2 and 12.2.4 of Chapter 12 – Documentation
- Revised Section 508: Chapter 5 – 501.1 Scope, 504.2 Content Creation or Editing, and Chapter 6 – 602.3 Electronic Support Documentation.

**Note**: When reporting on conformance with the WCAG 2.x Success Criteria, they are scoped for full pages, complete processes, and accessibility-supported ways of using technology as documented in the [WCAG 2.1 Conformance Requirements](https://www.w3.org/TR/WCAG21/#conformance-reqs).

### Table 1: Success Criteria, Level A

<table id="WCAG">
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level </strong></th>
<th><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr id="non-text-content" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all"><strong>1.1.1 Non-text Content</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.1.1 (Web)</li>
<li>10.1.1.1 (non-web document)</li>
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
Most in-line images supplied in article content provide alternative text, or descriptions, or figure captions. We are working towards full support.  
<br><br>
Some images, such as icons on user interface elements, are known to have inadequate or missing text alternatives. We are actively working to find and repair these problems. 
<br><br>
We mark up some images so that they can be ignored by Assistive Technologies if they are <a href="https://www.w3.org/TR/WCAG21/#dfn-pure-decoration"><i>pure decoration</i></a> (as defined by WCAG 2.1).
<br><br>
The SpringerLink checkout process pages are rendered in two separate designs. We are in the process of transferring all content from the older design (located at checkout.springer.com) to the newer design (located at order.springer.com). 
<br><br>
The <strong>old</strong> checkout design at checkout.springer.com presents inline images with no alternative text. Background images that are used to convey meaning (e.g. images to signify which credit cards we accept) are not supplemented with text or accessible names and cannot be perceived by users of Assistive Technology. Icon fonts are used in these pages that are not hidden from Assistive Technology; in some user agents, these may be inappropriately announced (e.g. the "cart" icon on the checkout button). The "remove from cart" button has no accessible name and cannot be understood by users of Assistive Technology. 
<br><br>
 The <strong>new</strong> checkout design at order.springer.com resolves all of the issues noted above.
<br><br>
Third party scripts may inject non-text content without text alternatives, or with inadequate text alternatives. These may include images in advertising scripts, and in the OneTrust "manage cookies" privacy centre. When we become aware of deficiencies, we contact third party suppliers to request repairs.
</td>
</tr>
<tr id="audio-only-and-video-only-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.1 (Web)</li>
<li>10.1.2.1 (non-web document)</li>
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
SpringerLink offers multimedia content through the third party MovingImage platform, or as downloadable video files in various formats. 
<br><br>
Video-only and audio-only content are generally used to support text-based content. 
<br><br>
We currently have no method of confirming the inclusion - or not - of adequate media alternatives or transcripts.
</td>
</tr>
<tr id="captions-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions"><strong>1.2.2 Captions (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.2 (Web)</li>
<li>10.1.2.2 (non-web document)</li>
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
<td>Partially supports</td>
<td>
SpringerLink offers multimedia content through the third party MovingImage platform, or as downloadable video files in various formats. 
<br><br>
Captions and/or transcripts maybe be provided for some pre-recorded content in journals, books, series, protocols, reference works or proceedings, but we currently have no method of confirming the inclusion - or not - of transcripts or captions. 
<br><br>
"Springer Nature Video" learning content published at link.springer.com/video uses the third party MovingImage platform. Both captions and transcripts are available. 
</td>
</tr>
<tr id="audio-description-or-media-alternative-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.3 (Web)</li>
<li>10.1.2.3 (non-web document)</li>
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
SpringerLink offers multimedia content through the third party MovingImage platform, or as downloadable video files in various formats.
<br><br>
Audio description is not generally used across our content, but some media may be presented alongside media alternatives such as text descriptions of video content. 
<br><br>
We currently have no method of confirming the inclusion - or not - of adequate media alternatives.
</td>
</tr>
<tr id="info-and-relationships" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic"><strong>1.3.1 Info and Relationships</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.1 (Web)</li>
<li>10.1.3.1 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) may use unsemantic markup, including inadequate, misleading, or incorrectly-applied landmarks. Some UI controls (e.g. "next" and "previous" pagination controls on search results pages) lack accessible names. Pages may omit level one headings. 
<br><br>
On pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries), we generally use progressive enhancement techniques and semantically-correct markup so that information, structure, and relationships can be understood independently of presentation.
<br><br>
We make use of WAI-ARIA roles to support landmarks, and use WAI-ARIA roles and properties when required for more complex functionality such as popup menus and dialogs. 
<br><br>
Some complex functionality may omit required WAI-ARIA roles, states, or attributes, or misuse WAI-ARIA markup and techniques. We are actively working to find and repair these problems. 
<br><br>
Multiple landmarks of the same type without unique labels are used on pages rendered in both designs. 
<br><br>
The SpringerLink checkout process pages are rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages found at both checkout.springer.com and order.springer.com omit or use inappropriate headings and heading levels, including the use of unsemantic headings for visual effect. Multiple landmarks of the same type without unique labels are also found on these pages. 
<br><br>
Pages found at checkout.springer.com misapply HTML elements (e.g. label elements used for error messages), which may make it difficult for users of Assistive Technology to understand the structure and purpose of individual components. Some landmarks are incorrectly duplicated. 
<br><br>
Pages found at order.springer.com use form fields that rely solely on built-in browser error checking, which can lead to error messages being unavailable for users with older browser technology, or Assistive Technology that doesn't support these features. 
<br><br>
Some custom interactive components found at checkout.springer.com are marked up unsemantically, which prevents them from being used by keyboard alone and from being recognised by Assistive Technology (e.g. the "login" and language selection components at the top of each page).
<br><br>
Third party scripts may inject content with incorrect or absent information about structure and relationships. These may include content in advertising scripts, in the Freshdesk customer services widget, and in the OneTrust "manage cookies" privacy centre, among others.
</td>
</tr>
<tr id="meaningful-sequence" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence"><strong>1.3.2 Meaningful Sequence</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.2 (Web)</li>
<li>10.1.3.2 (non-web document)</li>
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
The meaning of the content on the pages of SpringerLink does not depend on the order of the sections.
</td>
</tr>
<tr id="sensory-characteristics" valign="top">
<td><strong><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-understanding">1.3.3 Sensory Characteristics</a></strong> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.3 (Web)</li>
<li>10.1.3.3 (non-web document)</li>
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
The pages found at link.springer.com generally do not depend solely on sensory characteristics such as shape, size, visual location, orientation, or sound to understand their content.
<br><br>
We make use of graphical icons on controls. Adjacent visible text labels or WAI-ARIA labels are generally provided.
<br><br>
Some icons (e.g. "next" and "previous" pagination controls on search results pages) in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) lack accessible names. Users who are unable to perceive these icons by their sensory characteristics may be unable to use these controls. We are in the process of transferring all content from the older design to the newer design, which will remove the reliance on sensory characteristics for understanding. 
<br><br>
Some complex images in journals, books, series, protocols, reference works and proceedings may rely on sensory characteristics to be understood. Examples may include images of charts, graphs, diagrams, or maps. Generally, these images are used to supplement text content. 
<br><br>
Images found at checkout.springer.com that are used to convey meaning (e.g. images to signify which credit cards we accept) are not supplemented with text and cannot be perceived by users of Assistive Technology. These issues are resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
<br><br>
The Freshdesk customer services widget uses controls without accessible names. We are actively working to solve this problem. Additionally, we have provided alternate means of accessing customer services on our "Contact Us" page, including a contact email address, a support ticket system, and helpdesk telephone numbers.
</td>
</tr>
<tr id="use-of-color" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color"><strong>1.4.1 Use of Color</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.1 (Web)</li>
<li>10.1.4.1 (non-web document)</li>
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
Colour alone is generally not used to convey information in the pages of this product.
<br><br>
Links and icons may use colour to indicate hover or active states. These are supplemented with visible focus rings and/or background colours and/or text decoration underlines and/or luminosity differences per WAI techniques <a href="https://www.w3.org/WAI/WCAG21/Techniques/general/G183">G183</a> and <a href="https://www.w3.org/WAI/WCAG21/Techniques/css/C15">C15</a>.
<br><br>
Some complex images in journals, books, series, protocols, reference works and proceedings may rely on colour as the only visual means of understanding information. Examples may include images of charts, graphs, diagrams or maps. Generally, these images are used to supplement text content. 
</td>
</tr>
<tr id="audio-control" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio"><strong>1.4.2 Audio Control</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.2 (Web)</li>
<li>10.1.4.2 (non-web document)</li>
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
<td>Partially Supports</td>
<td>
Content supplied by us does not play automatically. 
<br><br>
All video with audio hosted through the third party MovingImage platform has a mechanism for pausing, stopping, and controlling volume. 
<br><br>
We do not support the playing of audio-only directly on our pages. Audio files hosted by us are supplied as downloadable files only, for use in the users' own media player. 
<br><br>
Third party advertisements may load video and audio that automatically starts, and may not provide adequate controls for pausing, stopping, and/or controlling volume. When we become aware of active advertisements with these problems, we immediately take steps to remove those advertisements from our pages.
</td>
</tr>
<tr id="keyboard" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable"><strong>2.1.1 Keyboard</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.1 (Web)</li>
<li>10.2.1.1 (non-web document)</li>
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
<td>Partially Supports</td>
<td>
The majority of components in the SpringerLink website can be navigated by keyboard alone. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Mouse-dependent event handlers are used to display additional information relating to images displayed on the homepage and to icons in search results, which may make the purpose of these graphics difficult to discern for keyboard users. We are actively working to repair these problems. 
<br><br>
Mouse-dependent event handlers are used to display detailed information about the meaning of preview-only content on advanced search pages. We are actively working to repair these problems. 
<br><br>
Content contained inside tab interfaces (e.g. tables of contents in Books) cannot be operated by keyboard alone. We are actively working to repair these problems.  
<br><br>
Video content located at link.springer.com/video can generally be operated without the use of a mouse, but some video functions (including turning on closed captions) cannot be operated by keyboard alone. Additionally, keyboard users are unable to toggle between the "details" and "transcript" tabs below the video. We are actively working to repair these problems.  
<br><br>
The SpringerLink checkout process pages are rendered in two separate designs. We are in the process of transferring all content from the older design (located at checkout.springer.com) to the newer design (located at order.springer.com). 
<br><br>
At checkout.springer.com, mouse-dependent event handlers are used to display detailed information about sales tax for purchases, although the subtotals and totals are displayed to all users at all times. 
<br><br>
Some components on pages located at checkout.springer.com can’t used by keyboard alone (e.g. the “login” and language selection components at the top of each page).
<br><br>
All components on pages located at order.springer.com can be operated by keyboard alone. We are in the process of transferring all checkout content to this new design. 
<br><br>
Third party advertising scripts may inject content that cannot be interacted with easily or at all by keyboard.
<br><br>
The Freshdesk customer services widget cannot be interacted with easily by keyboard alone. We are actively working to solve this problem. Additionally, we have provided alternate means of accessing customer services on our "Contact Us" page, including a contact email address, a support ticket system, and helpdesk telephone numbers. 
<br><br>
When we become aware of deficiencies, we contact third party suppliers to request repairs. Additionally, where possible, we aim to provide equivalent alternatives to problematic content. 
</td>
</tr>
<tr id="no-keyboard-trap" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping"><strong>2.1.2 No Keyboard Trap</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.2 (Web)</li>
<li>10.2.1.2 (non-web document)</li>
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
Keyboard trapping inside components on SpringerLink pages is rare, and in most cases is managed appropriately, allowing focus to be moved away from any component using standard keystrokes (<kbd>tab</kbd>, <kbd>shift</kbd>, <kbd>esc</kbd>). 
<br><br>
Modal dialogs (including those generated by third party scripts) may trap focus and provide inadequate methods of escaping. When we become aware of deficiencies, we actively work on repairs of our own, and with third party vendors where required.
</td>
</tr>
<tr id="character-key-shortcuts" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#character-key-shortcuts"><strong>2.1.4 Character Key Shortcuts</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1.4 (Web)</li>
<li>10.2.1.4 (non-web document)</li>
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
<tr id="timing-adjustable" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors"><strong>2.2.1 Timing Adjustable</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2.1 (Web)</li>
<li>10.2.2.1 (non-web document)</li>
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
<tr id="pause-stop-hide" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-pause"><strong>2.2.2 Pause, Stop, Hide</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2.2 (Web)</li>
<li>10.2.2.2 (non-web document)</li>
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
Any moving, blinking or scrolling content on SpringerLink pages generally does not start automatically, and is complemented by controls that allow users to pause or otherwise stop the content. Moving images in the form of gifs may not meet this criterion. 
<br><br>
Third party advertising scripts may inject content that automatically moves or blinks and lasts more than five seconds, without providing a mechanism to pause, stop, or hide that content. 
</td>
</tr>
<tr id="three-flashes-or-below-threshold" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate"><strong>2.3.1 Three Flashes or Below Threshold</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.3.1 (Web)</li>
<li>10.2.3.1 (non-web document)</li>
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
<tr id="bypass-blocks" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-skip"><strong>2.4.1 Bypass Blocks</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.1 (Web)</li>
<li>10.2.4.1 (non-web document) – Does not apply</li>
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
The pages found at link.springer.com generally use semantically-correct markup so that Assistive Technology users can recognise elements and move around them accordingly. We make use of WAI-ARIA roles to support landmarks. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Pages located at both checkout.springer.com and order.springer.com have landmarks present. Some are duplicated without unique labels. Some landmarks found at checkout.springer.com are malformed, and may be difficult to use. 
</td>
</tr>
<tr id="page-titled" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title"><strong>2.4.2 Page Titled</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.2 (Web)</li>
<li>10.2.4.2 (non-web document)</li>
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
<td>Partially Supports</td>
<td>
SpringerLink pages mostly have unique page titles that describe the purpose of the page.
<br><br>
Where multiple versions of the same content exist (e.g. in original research with a separate updated version), the page titles do not differentiate between versions. 
</td>
</tr>
<tr id="focus-order" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order"><strong>2.4.3 Focus Order</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.3 (Web)</li>
<li>10.2.4.3 (non-web document)</li>
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
The meaning and/or operation of content on SpringerLink is generally unaffected by focus order. 
<br><br>
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Some pages rendered in the <strong>older</strong> design may contain components where some items in the focus order do not match the visual order (for example the "date published" filtering on search results pages). 
<br><br>
On pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries), the focus order of page content matches the visual order.
<br><br>
Some pages located at checkout.springer.com contain components where the focus order does not match the visual order (for example the "terms" link on the registration page visually appears at the bottom of the registration form, but appears directly after the page header in the source/focus order).
<br><br>
Form labels located at order.springer.com are placed after their associated form fields in the source order, which does not match the visual order. Screen reader users moving through the form element by element may access the label after the input field instead of before, though all input fields are correctly associated with their labels. 
<br><br>
Third party scripts including advertising scripts or customer services widgets (among others), may inject content where the focus order does not match the visual order. The operation and meaning of these components should be unaffected by the focus order. 
</td>
</tr>
<tr id="link-purpose-in-context" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs"><strong>2.4.4 Link Purpose (In Context)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.4 (Web)</li>
<li>10.2.4.4 (non-web document)</li>
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
Generally, the purpose of each link found at link.springer.com can be determined by its descriptive text label. Most linked images or icons have alternative text or supplementary text labels. Some images, such as icons on user interface elements, are known to have inadequate or missing text alternatives. We are actively working to find and repair these problems.  
<br><br>
When citing references in articles, the link text contains only the year of the reference's publication. This may provide inadequate context for screen reader users. A title attribute is provided on these links, but the title attribute may not be made available by all Assistive Technologies.
<br><br>
In articles, anchor links that refer to same-page supplementary figures or tables use only the number of the supplementary material as their link text (e.g. "Figure 1" will be linked to only by the number "1"). This is likely to be insufficient context for screen reader users. 
<br><br>
Images located at checkout.springer.com lack accessible text, and do not provide adequate context when they are used as links. These issues are resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
<br><br>
Third party scripts including advertising scripts or customer services widgets (among others), may inject content that includes links with no accessible text, or poorly-named accessible text. When we become aware of deficiencies, we contact third party suppliers to request repairs or are actively seeking solutions. Additionally, where possible, we aim to provide equivalent alternatives to problematic content.
</td>
</tr>
<tr id="pointer-gestures" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-gestures"><strong>2.5.1 Pointer Gestures</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.1 (Web)</li>
<li>10.2.5.1 (non-web document)</li>
<li>11.2.5.1 (Open Functionality Software)</li>
<li>11.2.5.1 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Not Applicable</td>
<td>This product does not contain any functionality that uses multipoint or path-based gestures for operation.</td>
</tr>
<tr id="pointer-cancellation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#pointer-gestures"><strong>2.5.2 Pointer Cancellation</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.2 (Web)</li>
<li>10.2.5.2 (non-web document)</li>
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
<td><a href="https://www.w3.org/TR/WCAG21/#label-in-name"><strong>2.5.3 Label in Name</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.3 (Web)</li>
<li>10.2.5.3 (non-web document)</li>
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
In most cases where controls contain visible text, that text is also the label for the control, with limited exceptions. 
<br><br>
Images of product covers (e.g. journals, books displayed on the homepage of link.springer.com) used as links may contain text that does not meet this criterion. On the homepage, these images are supplemented with visible text labels (but the text is triggered by mouse-dependent event handlers, and their visibility cannot be toggled by the keyboard).
<br><br>
In pages rendered in all designs, some controls without text but with high recognisability (e.g. "next" and "previous" pagination controls on search results pages, the "play" button on the video player at link.springer.com/video) have inadequate or absent accessible names. 
</td>
</tr>
<tr id="motion-actuation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#motion-actuation"><strong>2.5.4 Motion Actuation</strong></a> (Level A 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.5.4 (Web)</li>
<li>10.2.5.4 (non-web document)</li>
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
<tr id="language-of-page" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id"><strong>3.1.1 Language of Page</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.1.1 (Web)</li>
<li>10.3.1.1 (non-web document)</li>
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
<td>Partially Supports</td>
<td>
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) may be switched by the user between English and German. These pages use the language attribute on the HTML element to indicate which language is being used as the default language of a page. 
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) are presented in English only, with the correct language attribute applied to the HTML element. 
<br><br>
Pages located at checkout.springer.com may also be switched by the user between English and German. These pages use the language attribute on the HTML element, but incorrectly present the default language of the page as English at all times (i.e. even when the user selects German). The new version of the checkout process design at order.springer.com is presented in English only, so this criterion does not apply; we are in the process of transferring all checkout content to the new design. 
</td>
</tr>
<tr id="on-focus" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus"><strong>3.2.1 On Focus</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.1 (Web)</li>
<li>10.3.2.1 (non-web document)</li>
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
<td>Supports</td>
<td>Components in the interface of the pages of this product that receive focus do not initiate a change of context.</td>
</tr>
<tr id="on-input" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-unpredictable-change"><strong>3.2.2 On Input</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.2 (Web)</li>
<li>10.3.2.2 (non-web document)</li>
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
<td>Supports</td>
<td>Changing the setting of any user interface component does not automatically cause a change of context on any of the pages of this product.</td>
</tr>
<tr id="error-identification" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-identified"><strong>3.3.1 Error Identification</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.1 (Web)</li>
<li>10.3.3.1 (non-web document)</li>
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
Where user input errors are automatically detected by our own software, those errors are identified with warning text adjacent to the input field. We do not rely on visual characteristics alone (e.g. colour) to indicate user input errors. 
<br><br>
In some parts of the site, we additionally use an <code>aria-describedby</code> property to associate error messages with invalid fields.
<br><br>
User account pages located at link.springer.com/account and pages located at checkout.springer.com use unsemantic, unassociated, label elements to mark up errors. 
<br><br>
Pages located at order.springer.com rely solely on built-in browser error checking, and do not identify errors in text. Some users with and without Assistive Technology may be unable to access these error states. 
</td>
</tr>
<tr id="labels-or-instructions" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues"><strong>3.3.2 Labels or Instructions</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.2 (Web)</li>
<li>10.3.3.2 (non-web document)</li>
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
<td>Partially Supports</td>
<td>
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) generally display visible and appropriately associated labels for input fields. Exceptions include the pagination number field on advanced search results pages and in the main search component in the page banner, both of which omit any label or WAI-ARIA description, and use only placeholder text as instruction. We are actively working to find and repair these problems.  
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) generally display visible and appropriately associated labels for input fields. 
<br><br>
Instructions such as those that explain mandatory fields may be absent or only present at the end of forms. (e.g. some payment information pages). Additional instructions for specific input fields may not be adequately associated (e.g. with <code>aria-describedby</code>) with the fields they describe. We are actively working to find and repair these problems. 
</td>
</tr>
<tr id="parsing" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses"><strong>4.1.1 Parsing</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.1 (Web)</li>
<li>10.4.1.1 (non-web document)</li>
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
Most of the pages found at link.springer.com generally use semantically-correct markup that meets the HTML5 specification for interface elements.
<br><br>
Where errors exist, they are usually minor, such as the presence of invalid <code>alt</code> and <code>src</code> attributes in SVG image nodes (ignored by user agents). There are some instances of incorrectly-nested elements (e.g. "<a href="https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content">flow content</a>" wrapped in "<a href="https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Phrasing_content">phrasing content</a>").
<br><br> 
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) have a slightly higher volume of parsing errors, which include more problematic errors such as <code>li</code> elements outside of <code>ul</code> elements and duplicate IDs, that may interfere with the ability of Assistive Technology to correctly identify some components. 
<br><br>
Ancillary static pages (e.g. the pages linked to at the footer of each page, such as Terms and Conditions, Legal Information, and Accessibility, among others) are hand-built in HTML, without the use of a dynamic templating system. Hand-built content may contain unclosed or illegally nested elements. When we become aware of content with these problems, we immediately take steps to repair the HTML.
<br><br>
Pages located at checkout.springer.com contain minor parsing errors, including incorrect placement of meta charset declarations. 
<br><br>
Pages located at order.springer.com contain parsing errors that may be problematic for Assistive Technology, including illegally-nested elements, invalid autocomplete values, and incomplete closing tags. 
<br><br>
Third party advertising scripts may inject content that omits start and end tags, contains duplicate attributes or illegally nested elements. When we become aware of active advertisements with these problems, we immediately take steps to remove those advertisements from our pages.
</td>
</tr>
<tr id="name-role-value" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv"><strong>4.1.2 Name, Role, Value</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.2 (Web)</li>
<li>10.4.1.2 (non-web document)</li>
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
The pages found at link.springer.com generally use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
In some cases, WAI-ARIA attributes have been omitted where they would be helpful (e.g. no status update is triggered on the "date published" popup component on advanced search pages). In other cases WAI-ARIA roles or attributes may be misused in ways that cause elements to have misleading semantics. We are actively working to find and repair these problems. 
<br><br>
Pages located at checkout.springer.com contain elements without accessible names (e.g. links, images), incorrectly-applied semantics (e.g. semantic headings used for visual effect only, malformed WAI-ARIA landmarks, labels used in incorrect contexts, data tables not marked up as tables, lists not marked up as lists, custom interactive components not marked up in a way that can be used by Assistive Technology), and missing elements or WAI-ARIA attributes (e.g. form fields without labels, step counters and flyout menus without WAI-ARIA markup). 
<br><br>
Other third party scripts, including the Freshdesk customer services widget, may present elements that lack adequate names and roles, making them difficult for screen reader users to access. When we become aware of deficiencies, we contact third party suppliers to request repairs.
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
<tr id="captions-live" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-real-time-captions"><strong>1.2.4 Captions (Live)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.4 (Web)</li>
<li>10.1.2.4 (non-web document)</li>
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
<tr id="audio-description-prerecorded" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only"><strong>1.2.5 Audio Description (Prerecorded)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.2.5 (Web)</li>
<li>10.1.2.5 (non-web document)</li>
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
<td>We do not generally provide audio description for prerecorded video. A limited form of audio description may be provided for some pre-recorded content, but we currently have no method of confirming the inclusion - or not - of audio description.
</td>
</tr>
<tr id="orientation" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#orientation"><strong>1.3.4 Orientation</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.4 (Web)</li>
<li>10.1.3.4 (non-web document)</li>
<li>11.1.3.4 (Open Functionality Software)</li>
<li>11.1.3.4 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>The SpringerLink website does not contain any content that restricts its view and operation to a single display orientation, such as portrait or landscape.</td>
</tr>
<tr id="identify-input-purpose" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#identify-input-purpose"><strong>1.3.5 Identify Input Purpose</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.3.5 (Web)</li>
<li>10.1.3.5 (non-web document)</li>
<li>11.1.3.5 (Open Functionality Software)</li>
<li>11.1.3.5 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Does not support</td>
<td>A limited number of form fields may have autocomplete values that allow the field purpose to be determined programmatically, but we have not widely implemented this functionality.</td>
</tr>
<tr id="contrast-minimum" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast"><strong>1.4.3 Contrast (Minimum)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.3 (Web)</li>
<li>10.1.4.3 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) use gradient background images that do not meet minimum contrast requirements between the text and one or more of the gradient background colours. 
<br><br>
There are limited instances of promotional/call-to-action content (e.g. the "New books and journals are available every day" box on the homepage of link.springer.com) with poor contrast ratio.
<br><br>
Images of product covers (e.g. journals, books displayed on the homepage of link.springer.com) may contain text that does not meet WCAG AA contrast guidelines. On the homepage, these images are supplemented with visible text labels (but the text is triggered by mouse-dependent event handlers, and their visibility cannot be toggled by the keyboard). 
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) meet WCAG AA contrast ratio requirements. 
<br><br>
Most text and images of text in the newer design have a contrast ratio of at least 4.5:1. Links generally fall slightly short of WCAG AA requirements, with a contrast ratio of 4.3:1. 
<br><br>
Gradient background images are used throughout checkout.springer.com, with insufficient contrast between the text and one or more of the gradient background colours. These issues are resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
<br><br>
Third party advertising scripts may inject content with insufficient contrast.
</td>
</tr>
<tr id="resize-text" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale"><strong>1.4.4 Resize text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.4 (Web)</li>
<li>10.1.4.4 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) can generally be resized without Assistive Technology up to 200 percent without loss of content or functionality. 
<br><br>
The flyout "search" and "menu" components in the header of the older design have fixed positions which may prevent users browsing with high magnification from being able to scroll through the page while the components are open. In the case of the "menu" component, only some of the menu can be used at high magnification, with the lower items cut off-screen. 
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) can be resized without Assistive Technology up to 400 percent without loss of content or functionality. 
<br><br>
Pages located at checkout.springer.com are not fully responsive and require horizontal scrolling at 200 percent magnification in order to read all content. Some footer menu items are removed for users browsing at high magnification, including the link to the Order FAQ. Users browsing with high magnification will be unable to access this content without returning to the main Springer website (<em>not</em> the SpringerLink website). These issues are resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
<br><br>
Third party advertising scripts may inject non-responsive content that loses or obscures information when text is resized.
</td>
</tr>
<tr id="images-of-text" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-text-presentation"><strong>1.4.5 Images of Text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.5 (Web)</li>
<li>10.1.4.5 (non-web document)</li>
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
Content in journals, books, series, protocols, reference works or proceedings may include complex images that contain images of text. In most cases these images are used to supplement the text content they appear alongside. In some cases (e.g. charts, graphs, or maps, among others), the text content presented alongside may be insufficient to explain the contents of the image. 
<br><br>
Images of product covers (e.g. journals or books displayed on the homepage of link.springer.com) may contain text. On the homepage, these images are supplemented with visible text labels, but the text is triggered by mouse-dependent event handlers, and their visibility cannot be toggled by the keyboard alone. 
<br><br>
Third party advertising scripts may inject images containing images of text.
</td>
</tr>
<tr id="reflow" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#reflow"><strong>1.4.10 Reflow</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.10 (Web)</li>
<li>10.1.4.10 (non-web document)</li>
<li>11.1.4.10.1 (Open Functionality Software)</li>
<li>11.1.4.10.2 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Supports</td>
<td>All parts of this product are responsive. Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions per the specifications in this criterion.</td>
</tr>
<tr id="non-text-contrast" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#non-text-contrast"><strong>1.4.11 Non-text Contrast</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.11 (Web)</li>
<li>10.1.4.11 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) contain user interface icons that do not meet minimum contrast requirements for non-text content. 
<br><br>
Some complex non-text images in journals, books, series, protocols, reference works and proceedings may have insufficient contrast. Examples may include images of charts, graphs, diagrams, or maps. Generally, these images are used to supplement text content.
</td>
</tr>
<tr id="text-spacing" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#text-spacing"><strong>1.4.12 Text Spacing</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.12 (Web)</li>
<li>10.1.4.12 (non-web document)</li>
<li>11.1.4.12 (Open Functionality Software)</li>
<li>11.1.4.12 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>
No loss of content or functionality occurs by setting the text spacing properties specified by this criterion anywhere in this product, except for the search results page where a collision may occur between some of the filters. 
<br><br>
The search results page is rendered in an older design - we are in the process of transferring this content from the older design to the newer design which will pass this criterion. 
</td>
</tr>
<tr id="content-on-hover-or-focus" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#content-on-hover-or-focus"><strong>1.4.13 Content on Hover or Focus</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.1.4.13 (Web)</li>
<li>10.1.4.13 (non-web document)</li>
<li>11.1.4.13 (Open Functionality Software)</li>
<li>11.1.4.13 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Does Not Support</td>
<td>
The search results page contains three tooltip components that toggle visibility on both hover and focus events. The tooltip components do not meet the Dismissable, Hoverable, or Persistent requirements specified by this criterion.
<br><br>
No other examples of components that trigger visibility of additional information on hover or focus exist in the pages of this product. 
</td>
</tr>
<tr id="multiple-ways" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-mult-loc"><strong>2.4.5 Multiple Ways</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.5 (Web)</li>
<li>10.2.4.5 (non-web document) – Does not apply</li>
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
<td>Partially Supports</td>
<td>
Users may use the search function or the provided category browsing links to access any part of this product. The main navigation component can also be used to access the main content index pages.
<br><br>
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
The flyout "menu" component in the header of the older design has a fixed position which may prevent users browsing with high magnification from being able to access all items in the menu. 
<br><br>
On pages located at checkout.springer.com, some footer menu items are removed for users browsing at high magnification, including the link to the Order FAQ. Users browsing with high magnification will be unable to access this content without returning to the main Springer website (<em>not</em> the SpringerLink website). This issue is resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
</td>
</tr>
<tr id="headings-and-labels" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive"><strong>2.4.6 Headings and Labels</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.6  (Web)</li>
<li>10.2.4.6 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) may incorrectly use label elements for other purposes (e.g. for error messages on account management pages), omit labels for some functionality (e.g. the pagination number field on advanced search results pages and the text input for the main search component in the page banner). 
<br><br>
Level one headings are omitted on some pages (e.g. search results pages). Other pages have multiple level one headings (e.g. static ancillary pages such as link.springer.com/termsandconditions). 
<br><br>
We are actively working to find and repair these problems.  
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) use correctly-structured headings and generally display visible and appropriately associated labels for input fields. 
<br><br>
Pages found at checkout.springer.com omit or use inappropriate headings and heading levels, including the use of unsemantic headings for visual effect, skipping heading levels, and providing empty headings. Pages at this location also misapply HTML elements (e.g. label elements used for error messages), which may make it difficult for users of Assistive Technology to understand the structure and purpose of individual components. These issues are resolved in the new version of the checkout process design at order.springer.com; we are in the process of transferring all checkout content to the new design. 
<br><br>
The Freshdesk customer services widget injects controls with inadequate labels, making it difficult or impossible to use the controls with Assistive Technology. We are actively working to solve this problem. Additionally, we have provided alternate means of accessing customer services on our "Contact Us" page, including a contact email address, a support ticket system, and helpdesk telephone numbers.
</td>
</tr>
<tr id="focus-visible" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible"><strong>2.4.7 Focus Visible</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4.7 (Web)</li>
<li>10.2.4.7 (non-web document)</li>
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
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) use default browser focus rings only for interactive components. 
<br><br>
Pages rendered in the <strong>newer</strong> design (currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries) use highly-visible focus styles, including yellow focus rings or yellow backgrounds.
<br><br>
Pages found at order.springer.com use default browser focus rings only for interactive components. 
<br><br>
Third party scripts, including advertising, may inject components that remove focus styles.
</td>
</tr>
<tr id="language-of-parts" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id"><strong>3.1.2 Language of Parts</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.1.2 (Web)</li>
<li>10.3.1.2 (non-web document)</li>
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
<td>
Content in journals, books, series, protocols, reference works or proceedings may include or be completely composed of text in languages other than that defined in the HTML <code>lang</code> attribute. We currently have no method of confirming the inclusion - or not - of appropriate <code>lang</code> attributes for pieces of text that may use a different language to the main document. 
<br><br>
Titles in the cart at checkout.springer.com and order.springer.com may be in multiple languages. The correct <code>lang</code> attribute for titles in a language different to that of the overall document is omitted. 
<br><br>
Third party scripts may inject components that use a different language to the page content - for example a targeted advertisement may use the native language of the user, and not be marked up with a separate <code>lang</code> attribute.
</td>
</tr>
<tr id="consistent-navigation" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations"><strong>3.2.3 Consistent Navigation</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.3 (Web)</li>
<li>10.3.2.3 (non-web document) – Does not apply</li>
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
<td>Partially Supports</td>
<td>
The SpringerLink website contains content that is rendered in two separate, inconsistent designs. The designs have different navigation methods, within the same collections of pages. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design are currently Journals, and ancillary pages such as search, indexes, and account management. 
<br><br>
Pages rendered in the <strong>newer</strong> design are currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries. 
<br><br>
When the transfer process is complete, the navigation methods between designs will be broadly consistent. 
<br><br>
Pages located at checkout.springer.com and order.springer.com are rendered in two separate, inconsistent designs. We are in the process of transferring all checkout content to this new design. Both checkout configurations deal with sensitive information and have intentionally been made more simple in design, and do not share the same navigation system as the main site. The navigation of these sets of pages is internally consistent. 
</td>
</tr>
<tr id="consistent-identification" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality"><strong>3.2.4 Consistent Identification</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.2.4 (Web)</li>
<li>10.3.2.4 (non-web document) – Does not apply</li>
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
<td>Partially Supports</td>
<td>
The SpringerLink website contains content that is rendered in two separate, inconsistent designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design are currently Journals, and ancillary pages such as search, indexes, and account management. 
<br><br>
Pages rendered in the <strong>newer</strong> design are currently Articles, Chapters, Books, Book Series, Reference Works, and Reference Work Entries. 
<br><br>
When the transfer process is complete, content will use a unified design style with consistent presentation and functionality.
<br><br>
Pages located at checkout.springer.com and order.springer.com are rendered in two separate, inconsistent designs. We are in the process of transferring all checkout content to this new design. Both checkout configurations deal with sensitive information and have intentionally been made more simple in design, and do not share the same navigation system as the main site. The presentation of these sets of pages is internally consistent, and the tasks performed are unlike those performed elsewhere on the site. 
</td>
</tr>
<tr id="error-suggestion" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions"><strong>3.3.3 Error Suggestion</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.3 (Web)</li>
<li>10.3.3.3 (non-web document)</li>
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
Where user input errors are automatically detected by our own software, those errors are identified to the user with warning text adjacent to the input field. Unless it would present a risk to security, the warning text describes the error and what the user should do to correct it. 
<br><br>
The SpringerLink website contains content that is rendered in two separate designs. We are in the process of transferring all content from the older design to the newer design. 
<br><br>
Pages rendered in the <strong>older</strong> design (currently Journals, and ancillary pages such as search, indexes, and account management) use unsemantic, unassociated label elements to mark up errors.
<br><br>
Pages located at checkout.springer.com also use unsemantic, unassociated label elements to mark up errors.

<br><br>
Pages located at order.springer.com rely solely on built-in browser error checking, and do not identify errors in text. Some users with and without Assistive Technology may be unable to access these error states. 
</td>
</tr>
<tr id="error-prevention-legal-financial-data" valign="top">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.3.3.4 (Web)</li>
<li>10.3.3.4 (non-web document)</li>
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
<td>Payment pages at checkout.springer.com and order.springer.com have a checkout flow that includes a verification step. There, the user must confirm that their choices are correct before they may enter their payment details. At this stage they may return to a previous step to make corrections, cancel, or abandon the process.</td>
</tr>
<tr id="status-messages" valign="top">
<td><a href="https://www.w3.org/TR/WCAG21/#status-messages"><strong>4.1.3 Status Messages</strong></a> (Level AA 2.1 only)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.4.1.3 (Web)</li>
<li>10.4.1.3 (non-web document)</li>
<li>11.4.1.3 (Open Functionality Software)</li>
<li>11.4.1.3 (Closed Software) – Does not apply</li>
<li>11.8.2 (Authoring Tool)</li>
<li>12.1.2 (Product Docs)</li>
<li>12.2.4 (Support Docs)</li>
</ul>
<em>Revised Section 508 - does not apply</em>
</td>
<td>Partially Supports</td>
<td>Status messages that do not receive focus are presented in text. Some are marked up with programmatic roles (e.g. `role="alert"` on some error messages), but there is no consistent, single approach to status messages across the multiple designs.   ARIA Live Regions are not generally used.</td>
 
</tr>
</tbody>
</table>

### Table 3: Success Criteria, Level AAA

Notes: This product has not been evaluated for WCAG 2.1 Level AAA conformance.

## Revised Section 508 Report

### Chapter 3: [Functional Performance Criteria](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-3-functional-performance-criteria) (FPC)

Notes: See [WCAG section](#wcag-20-report) for full details. 

| **Criteria**                                                   | **Conformance Level**    | **Remarks and Explanations** |
| -------------------------------------------------------------- | ---------------------    | ---------------------------- |
| 302.1 Without Vision                                           | Partially Supports       | The majority of content is marked up for Assistive Technology. Some pages and interactive components may be difficult to use. Third party scripts may inject content with inadequate accessible alternatives. |
| 302.2 With Limited Vision                                      | Partially Supports	    | Markup is written with support for Assistive Technology. Text is resizable by the user. The product does not impede the user from zooming into the page. Some functionality may be difficult to use at high magnification. Third party scripts may inject content with inadequate accessibility support. |
| 302.3 Without Perception of Color                              | Supports                 | Color perception is not needed to use this product. |
| 302.4 Without Hearing                                          | Partially Supports       | Some but not all audio is supported by captions or transcripts.  |
| 302.5 With Limited Hearing                                     | Partially Supports       | Some but not all audio is supported by captions or transcripts.  |
| 302.6 Without Speech                                           | Not Applicable	        | Speech is not needed to use this product. |
| 302.7 With Limited Manipulation                                | Partially Supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Fine motor control and simultaneous actions are not required to operate this product. Third party scripts may inject content that is difficult to use without a pointing device. |
| 302.8 With Limited Reach and Strength                          | Partially Supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Some content requires the use of a mouse. Third party scripts may inject content that is difficult to use without a pointing device. |
| 302.9 With Limited Language, Cognitive, and Learning Abilities | Partially Supports       | The pages of this product comprise multiple designs with inconsistent presentation between designs. Each design is internally consistent. Clear labels, titles, and accessible names are generally used for controls. Some pages lack accessible names for some controls and fail to explain the meanings of icons. Third party scripts may inject content with inconsistent or absent labelling of interface components. |

### Chapter 4: [Hardware](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-4-hardware)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter 5: [Software](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-5-platforms-and-applications)

Notes: See [WCAG section](#wcag-20-report) for full details. 

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
<td>501.1 Scope – Incorporation of WCAG 2.1 AA</td>
<td>See <a href="#WCAG">WCAG 2.1</a> section</td>
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
Object role, state(s), properties, boundary, name, and description are generally programmatically determinable, with some exceptions.
<br><br>
See WCAG sections <a href="#non-text-content">1.1.1 Non-text Content</a>, <a href="#info-and-relationships">1.3.1 Info and Relationships</a>, <a href="#sensory-characteristics">1.3.3 Sensory Characteristics</a>, <a href="#link-purpose-in-context">2.4.4 Link Purpose (In Context)</a>, <a href="#labels-or-instructions">3.3.2 Labels or Instructions</a>, <a href="#parsing">4.1.1 Parsing</a>, <a href="#name-role-value">4.1.2 Name, Role, Value</a>, <a href="#contrast-minimum">1.4.3 Contrast (Minimum)</a>, and <a href="#headings-and-labels">2.4.6 Headings and Labels</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.2 Modification of Object Information</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML or WAI-ARIA object roles for maximum compatibility with Assistive Technologies, with some exceptions.
<br><br>
See WCAG sections <a href="#non-text-content">1.1.1 Non-text Content</a>, <a href="#info-and-relationships">1.3.1 Info and Relationships</a>, <a href="#sensory-characteristics">1.3.3 Sensory Characteristics</a>, <a href="#link-purpose-in-context">2.4.4 Link Purpose (In Context)</a>, <a href="#labels-or-instructions">3.3.2 Labels or Instructions</a>, <a href="#parsing">4.1.1 Parsing</a>, <a href="#name-role-value">4.1.2 Name, Role, Value</a>, <a href="#contrast-minimum">1.4.3 Contrast (Minimum)</a>, and <a href="#headings-and-labels">2.4.6 Headings and Labels</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.3 Row, Column, and Headers</td>
<td>Partially Supports</td>
<td>
Data tables in journals, books, series, protocols, reference works or proceedings may not be marked up with adequate table header information.
<br><br>
Data tables in dynamic templates are rare, but where they do appear, they are marked up with standard HTML table elements. Row headers are present and associated with rows and columns as necessary.
</td>
</tr>
<tr>
<td>502.3.4 Values</td>
<td>Supports</td>
<td>The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td>502.3.5 Modification of Values</td>
<td>Supports</td>
<td>The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td>502.3.6 Label Relationships</td>
<td>Partially Supports</td>
<td>
Generally, the pages of this product use labels on components that require user input, with some exceptions.
<br><br>
See WCAG sections <a href="#headings-and-labels">2.4.6 Headings and Labels</a> and <a href="#labels-or-instructions">3.3.2 Labels or Instructions</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.7 Hierarchical Relationships</td>
<td>Partially Supports</td>
<td>
The pages of this product generally use standard HTML to express hierarchy, with some exceptions and errors. Third party scripts may inject content that obscures the relationships between components.
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a>, and <a href="#headings-and-labels">2.4.6 Headings and Labels</a> for further detail.
</td>
</tr>
<tr>
<td>502.3.8 Text</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard plain text in HTML.
<br><br>
Content in journals, books, series, protocols, reference works or proceedings may contain images of text without adequate programmatically determinable alternatives. 
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
<td>The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies.</td>
</tr>
<tr>
<td>502.3.11 Actions on Objects</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML or WAI-ARIA object attributes for maximum compatibility with Assistive Technologies. Some content, including that injected by third party scripts, cannot be interacted with easily or at all by keyboard or by other Assistive Technologies. 
<br><br>
See WCAG sections <a href="#info-and-relationships">1.3.1 Info and Relationships</a>, and <a href="#keyboard">2.1.1 Keyboard</a> for further detail. 
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
<td>The pages of this product use standard HTML elements and cursor controls for user input that may be overridden by Assistive Technology.</td>
</tr>
<tr>
<td>502.3.14 Event Notification</td>
<td>Partially Supports</td>
<td>
The pages of this product use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
Some components omit or misuse WAI-ARIA attributes in a way that prevents users of some Assistive Technologies from being able to perceive changes in state. We are actively working to find and repair these problems. 
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
<td>We do not provide any alternative user interface for this product that functions as Assistive Technology.</td>
</tr>
<tr>
<td><em><strong>503.4 User Controls for Captions and Audio Description</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>503.4.1 Caption Controls</td>
<td>Partially Supports</td>
<td>Not all video content provides captions. Where captions are provided, the controls for adjusting those captions are found at the same menu level as the user controls for volume or program selection. The controls cannot be operated by keyboard alone.</td>
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
| 4.2.9 Minimize photosensitive seizure triggers    | Supports                                                                                    | The pages of this product do not contain anything that flashes. |
| 4.2.10 Usage with limited cognition               | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.9 | See [Revised Section 508 Report Ch.3](#chapter-3-functional-performance-criteria-fpc) 302.9 |
| 4.2.11 Privacy                                    | Supports                                                                                    | Standard HTML and WAI-ARIA attributes are used on these pages. The product does not impede the user from using their own privacy tools when interacting with the content. |

### Chapter [5: Generic Requirements](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=23)

Notes: This product supports standard web Assistive Technologies and is therefore not subject to the Closed Functionality criteria described in this chapter.

### Chapter [6: ICT with Two-Way Voice Communication](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=28) 

Notes: This product does not offer two-way voice communication and is therefore not subject to the requirements of this chapter.

### Chapter [7: ICT with Video Capabilities](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=31) 

Notes: See [WCAG section](#wcag-20-report) for full details. 

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

Notes: Please see [WCAG 2.1 section](#WCAG).

### Chapter [10: Non-web Documents](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=43)

Notes: This product does not include non-web documents and is therefore not subject to the requirements of this chapter.


### Chapter [11: Software](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=53)

| **Criteria**                                                                                      | **Conformance Level**                                                                    | **Remarks and Explanations**                                                   |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 11.2.1 Software success criteria (excluding closed functionality)                                 | See [WCAG 2.1](#WCAG) section                                                            | See information in WCAG section                                                |
| 11.2.2 Software success criteria (closed functionality)                                           | See [WCAG 2.1](#WCAG) section                                                            | See information in WCAG section                                                |
| ***11.3 Interoperability with Assistive Technology***                                             | -                                                                                        | -                                                                              |
| ***11.3.1 Closed functionality (informative)***                                                   | -                                                                                        | -                                                                              |
| ***11.3.2 Accessibility services***                                                               | -                                                                                        | -                                                                              |
| ***11.3.2.1 Platform accessibility service support for software that provides a user interface*** | See 11.3.2.5 through 11.3.2.17                                                           | See information in 11.3.2.5 through 11.3.2.17                                  |
| ***11.3.2.2 Platform accessibility service support for Assistive Technologies***                  | See 11.3.2.5 through 11.3.2.17                                                           | See information in 11.3.2.5 through 11.3.2.17                                  |
| 11.3.2.3 Use of accessibility services                                                            | Supports                                                                                 | This product supports standard platform accessibility services.                |
| 11.3.2.4 Assistive Technology                                                                     | Not Applicable                                                                           | This product is not an Assistive Technology.                                   |
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

This document is provided for information purposes only and the contents hereof are subject to change without notice. Springer Nature does not warrant that this document is error free, nor does it provide any other warranties or conditions, whether expressed orally or implied in law, including implied warranties and conditions of merchantability or fitness for a particular purpose. Springer Nature specifically disclaims any liability with respect to this document and no contractual obligations are formed either directly or indirectly by this document. Springer Nature further makes no representation concerning the ability of Assistive Technologies or other products to interoperate with Springer Nature products. This document addresses the named product(s) or platforms only.
