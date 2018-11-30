# nature.com (content discovery pages) Accessibility Conformance Report

### **VPAT**&reg; **Version 2.2 – July 2018**

**Name of Product/Version**: nature.com (content discovery pages) _(we do not version our software)_  
**Product Description**: 
The nature.com content discovery pages are used to locate the latest research, reviews and news from across all of the Nature journals by subject. This report refers entirely to the accessibility of content that can be found at: [https://www.nature.com/subjects](https://www.nature.com/subjects)  
**Date**: 12th November 2018  
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
<th scope="col"><strong>Criteria</strong></th>
<th scope="col"><strong>Conformance Level </strong></th>
<th scope="col"><strong>Remarks and Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#text-equiv-all"><strong>1.1.1 Non-text Content</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.1 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
All images that we supply provide alternate text or descriptions; background images such as icons on user interface elements are identified in text.
<br><br>
We mark up some images so that they can be ignored by Assistive Technologies if they are [_pure decoration_](https://www.w3.org/TR/WCAG21/#dfn-pure-decoration) (as defined by WCAG 2.0).
<br><br>
Background images that we supply are always decorative.
<br><br>
Third party scripts may inject non-text content without text alternatives. These include images in advertising scripts and in the "manage cookies" privacy centre.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-av-only-alt"><strong>1.2.1 Audio-only and Video-only (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.2 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>Audio and video are not displayed in this product.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-captions"><strong>1.2.2 Captions (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.3 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>Audio and video are not displayed in this product.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc"><strong>1.2.3 Audio Description or Media Alternative (Prerecorded)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.4 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>Audio and video are not displayed in this product.</td>
</tr>
<tr id="info-and-relationships">
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-programmatic"><strong>1.3.1 Info and Relationships</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.7 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
We use progressive enhancement techniques and semantically-correct markup so that information, structure, and relationships can be understood independent of presentation.
<br><br>
We make use of ARIA roles to support landmarks, and use ARIA roles and properties when required for more complex functionality such as popup menus and search results updates.
<br><br>
Third party scripts may inject content with incorrect or absent information about structure and relationships. These include content in advertising scripts and in the "manage cookies" privacy centre.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#content-structure-separation-sequence"><strong>1.3.2 Meaningful Sequence</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.8 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>
The meaning of the content in the pages of this product does not depend on the order of the sections.
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>
The pages of this product do not depend solely on sensory characteristics such as shape, size, visual location, orientation, or sound to understand content.
<br><br>
Icons may be displayed to control functionality, but adjacent visible text labels or aria-labels are also provided to ensure that relationships are available to Assistive Technologies.
</td>
</tr>
<tr id="use-of-color">
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-without-color"><strong>1.4.1 Use of Color</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.10 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>
Colour alone is not used to convey information in the pages of this product.
<br><br>
Links and icons may use colour to indicate hover or active states. These are supplemented with visible focus rings and/or text decoration underlines and/or luminosity differences per WAI techniques [G183](https://www.w3.org/WAI/WCAG21/Techniques/general/G183) and [C15](https://www.w3.org/WAI/WCAG21/Techniques/css/C15).
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-dis-audio"><strong>1.4.2 Audio Control</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.11 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>
No audio is played on the pages of this product. 
</td>
</tr>
<tr id="keyboard">
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-keyboard-operable"><strong>2.1.1 Keyboard</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.15 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
All of the pages in this product can be navigated by keyboard alone. Complex elements like flyout menus can be exited with the <kbd>esc</kbd> key. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
Third party advertising scripts may inject content that can't be interacted with easily or at all by keyboard.
<br><br>
The "manage cookies" privacy centre banner (3rd party content) cannot be interacted with easily by keyboard alone. An alternative static link to the privacy centre is provided in the footer of each page.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#keyboard-operation-trapping"><strong>2.1.2 No Keyboard Trap</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.16 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>Focus can be moved away from any component on the page using standard keystrokes (<kbd>tab</kbd>, <kbd>shift</kbd>, <kbd>esc</kbd>).</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#time-limits-required-behaviors"><strong>2.2.1 Timing Adjustable</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.17 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not applicable</td>
<td>No moving, blinking, scrolling, or auto-updating information is included on the pages of this product.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#seizure-does-not-violate"><strong>2.3.1 Three Flashes or Below Threshold</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.19 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
</ul></td>
<td>Partially supports</td>
<td>
We use semantically-correct markup so that Assistive Technology users can recognise elements and move around them accordingly. We make use of ARIA roles to support landmarks. We also provide skip links for bypassing repetitive navigation elements.
<br><br>
The "manage cookies" privacy centre (3rd party content) does not provide a way for screen reader users to bypass the links in its left hand menu.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-title"><strong>2.4.2 Page Titled</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.21 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>All of the pages in this product have unique page titles that describe the purpose of the page.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-order"><strong>2.4.3 Focus Order</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.22 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
The meaning or operation of the pages in this product is generally unaffected by focus order. The focus order of all page content matches the visual order.
<br><br>
Third party advertising scripts may inject content where the focus order does not match the visual order.
</td>
</tr>
<tr id="link-purpose-in-context">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-refs"><strong>2.4.4 Link Purpose (In Context)</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.23 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
The purpose of each link that we provide can be determined by its descriptive text label; linked images or icons have alternative text or similar to provide this description.
<br><br>
Third party advertising scripts may inject content that includes links with no accessible text, or poorly-named accessible text.
<br><br>
The "manage cookies" privacy centre (3rd party content) displays some links with a title attribute instead of accessible text; the title attribute may not be made available by all Assistive Technologies.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-doc-lang-id"><strong>3.1.1 Language of Page</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.27 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>All of the pages in this product use the language attribute on the HTML element to specify the default language of a page.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-receive-focus"><strong>3.2.1 On Focus</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.29 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not applicable</td>
<td>Input errors are not automatically detected on the pages of this product.</td>
</tr>
<tr id="labels-or-instructions">
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-cues"><strong>3.3.2 Labels or Instructions</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.34 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Supports</td>
<td>
The main search component in the page banner has a visually hidden label associated with the search input field. The "find a subject" search component on the subjects index page has a visible label.
<br><br>
No other components on the pages of this product accept user input.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-parses"><strong>4.1.1 Parsing</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.37 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
The pages of this product use semantically-correct markup that meets the HTML5 specification for all interface elements.
<br><br>
Third party advertising scripts may inject content that omits start and end tags, contains duplicate attributes or contains illegally nested elements. When we become aware of active advertisements with these problems, we immediately take steps to remove that advertisement from our pages.
</td>
</tr>
<tr id="name-role-value">
<td><a href="http://www.w3.org/TR/WCAG20/#ensure-compat-rsv"><strong>4.1.2 Name, Role, Value</strong></a> (Level A)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.38 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
The pages of this product use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
The "manage cookies" privacy centre (third party content) uses an inappropriate aria label of "true" in place of its main heading, and both links and images exist with no accessible name. Additionally, when a screenreader user activates a link on the left hand menu of the Privacy Preference Centre, they are not made aware that the content on the right has updated. We have reported these problems to the vendor. 
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>Video is not displayed on the pages of this product.</td>
</tr>
<td><a href="http://www.w3.org/TR/WCAG20/#media-equiv-audio-desc-only"><strong>1.2.5 Audio Description (Prerecorded)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.6 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not Applicable</td>
<td>Video is not displayed on the pages of this product.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-contrast"><strong>1.4.3 Contrast (Minimum)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.12 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>All text and images of text supplied by us on the pages of this product have a contrast ratio of at least 4.5:1.
<br><br>
Third party advertising scripts may inject content with insuffucient contrast.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#visual-audio-contrast-scale"><strong>1.4.4 Resize text</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.13 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
The pages of this product never use images of text to convey information except in the case of [logotypes](https://www.w3.org/WAI/WCAG21/Understanding/images-of-text.html) (considered essential per WCAG 2.0) or when the image is [pure decoration](https://www.w3.org/TR/WCAG21/#dfn-pure-decoration).
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
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
</ul></td>
<td>Supports</td>
<td>Users may use the search function or the provided links to access any part of the subject pages. Breadcrumb menus are provided to return users to the index page. The main navigation component can also be used to access the main subject index pages.</td>
</tr>
<tr id="headings-and-labels">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-descriptive"><strong>2.4.6 Headings and Labels</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.25 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
Our document structure is semantically marked up using headings to create a sequential hierarchy of content. We never use inappropriate heading levels for visual effect. All of the pages of this product use labels on components that require user input. Sometimes headings or labels may be visually hidden but available to Assistive Technologies.
<br><br>
The "manage cookies" privacy centre (3rd party content) uses an inappropriate aria label of "true" in place of its main heading. We have reported this problem to the vendor.
</td>
</tr>
<tr id="focus-visible">
<td><a href="http://www.w3.org/TR/WCAG20/#navigation-mechanisms-focus-visible"><strong>2.4.7 Focus Visible</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.26 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>
We provide high-visibility yellow focus rings on all focusable elements. Some items (such as links) may use changes in text-decoration to indicate focus in addition to the focus ring.
<br><br>
Third party advertising scripts may inject components that remove focus styles.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#meaning-other-lang-id"><strong>3.1.2 Language of Parts</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.28 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Partially supports</td>
<td>All components on the pages of this product supplied by us use the same language defined in the HTML lang attribute, therefore Language of Parts is not applicable for the majority of this product.
<br><br>
Third party advertising scripts may inject components that use a different language to the page content - for example a targeted advertisment may use the native language of the user. These may not be marked up with a separate language attribute.
</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-locations"><strong>3.2.3 Consistent Navigation</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.31 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
</ul></td>
<td>Supports</td>
<td>These subject pages use the same navigation methods throughout.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#consistent-behavior-consistent-functionality"><strong>3.2.4 Consistent Identification</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.32 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software) – Does not apply to non-web software</li>
</ul></td>
<td>Supports</td>
<td>These subject pages use a unified design style with consistent presentation and functionality.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-suggestions"><strong>3.3.3 Error Suggestion</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.35 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not applicable</td>
<td>User input errors are not automatically detected.</td>
</tr>
<tr>
<td><a href="http://www.w3.org/TR/WCAG20/#minimize-error-reversible"><strong>3.3.4 Error Prevention (Legal, Financial, Data)</strong></a> (Level AA)
<br><br>Also applies to:<br><br>
<em>EN 301 549 Criteria</em>
<ul>
<li>9.2.36 (Web)</li>
</ul>
<em>Revised Section 508</em>
<ul>
<li>501 (Web)(Software)</li>
</ul></td>
<td>Not applicable</td>
<td>No data is saved by the pages of this product, and input errors are not automatically detected.</td>
</tr>
</tbody>
</table>

### Table 3: Success Criteria, Level AAA

Notes: This product has not been evaluated for WCAG 2.0 Level AAA conformance.

## Revised Section 508 Report

### Chapter 3: [Functional Performance Criteria](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-3-functional-performance-criteria) (FPC)

| **Criteria**                                                   | **Conformance Level**    | **Remarks and Explanations** |
| -------------------------------------------------------------- | ---------------------    | ---------------------------- |
| 302.1 Without Vision                                           | Partially supports       | The majority of content is marked up for Assistive Technology. Third party scripts may inject content with inadequate accessible alternatives. |
| 302.2 With Limited Vision                                      | Partially supports	    | Markup is written with support for assistive technology. Text is resizable by the user. Fonts are set as rems and use pixels as a fallback if not supported. The website does not impede the user from zooming into page. Third party scripts may inject content with inadequate accessible alternatives. |
| 302.3 Without Perception of Color                              | Supports                 | Color perception is not needed to use the website. |
| 302.4 Without Hearing                                          | Not Applicable	        | Audio is not used in this product. |
| 302.5 With Limited Hearing                                     | Not Applicable	        | Audio is not used in this product. |
| 302.6 Without Speech                                           | Not Applicable	        | Speech is not needed to use this product. |
| 302.7 With Limited Manipulation                                | Partially supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Fine motor control and simultaneous actions are not required to operate this product. Third party advertising scripts may inject content that is difficult to use without a pointing device. |
| 302.8 With Limited Reach and Strength                          | Partially supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Third party advertising scripts may inject content that is difficult to use without a pointing device. |
| 302.9 With Limited Language, Cognitive, and Learning Abilities | Partially supports       | The pages of this product have a consistent presentation with clear labels, titles, and accessible names for controls. Third party scripts may inject content with inconsistent or absent labelling of interface components. |

### Chapter 4: [Hardware](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-4-hardware)

Notes: This product is a web software application and is not subject to the requirements of this chapter.

### Chapter 5: [Software](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-5-platforms-and-applications)

<table>
<thead>
<tr>
<th><strong>Criteria</strong></th>
<th><strong>Conformance Level</strong></th>
<th><strong>Remarks and Explanations</strong></th>
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
<td>Not applicable</td>
<td>This product is not considered platform software as defined by Section 508. See [E103 Definitions, section E103.4](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines#E103-definitions).</td>
</tr>
<tr>
<td>502.2.2 No Disruption of Accessibility Features</td>
<td>Not applicable</td>
<td>
This product has no platform features as defined by Section 508. The product is compatible with operating system and browser accessibility features configured by the user.
<br><br>
Third party scripts may inject content that disrupts standard operating and browser accessibility features. See information in WCAG section for complete details.
</td>
</tr>
<tr>
<td><em><strong>502.3 Accessibility Services</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>502.3.1 Object Information</td>
<td>Partially supports</td>
<td>
Object role, state(s), properties, boundary, name, and description are generally programmatically determinable.
<br><br>
See WCAG sections [1.3.1 Info and Relationships](#info-and-relationships) and [4.1.2 Name, Role, Value](#name-role-value) for further detail.
</td>
</tr>
<tr>
<td>502.3.2 Modification of Object Information</td>
<td></td>
<td>
The pages of this product use standard HTML or ARIA object roles for maximum compatibility with assistive technologies.
<br><br>
See WCAG sections [1.3.1 Info and Relationships](#info-and-relationships) and [4.1.2 Name, Role, Value](#name-role-value) for further detail.
</td>
</tr>
<tr>
<td>502.3.3 Row, Column, and Headers</td>
<td>Not applicable</td>
<td>Data tables are not present in this product.</td>
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
<td>Supports</td>
<td>
All of the pages in this product use labels on components that require user input.
<br><br>
See WCAG sections [2.4.6 Headings and Labels](#headings-and-labels) and [3.3.2 Labels or Instructions](#labels-or-instructions) for further detail.
</td>
</tr>
<tr>
<td>502.3.7 Hierarchical Relationships</td>
<td>Partially supports</td>
<td>
The pages of this product generally use standard HTML to express hierarchy. Third party scripts may inject content that obscures the relationships between components.
<br><br>
See WCAG section [1.3.1 Info and Relationships](#info-and-relationships) for further detail.
</td>
</tr>
<tr>
<td>502.3.8 Text</td>
<td>Partially supports</td>
<td>
The pages of this product use standard plain text in HTML.
<br><br>
The "manage cookies" privacy centre (Third party content) uses an inappropriate aria label of "true" in place of its main heading. Some text in the privacy center (e.g. link text) may be present only in a title attribute, and may not be accessible to some assistive technologies.
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
<td>Partially supports</td>
<td>
The pages of this product use standard HTML or ARIA object attributes for maximum compatibility with assistive technologies.
<br><br>
Some third party scripts may inject content that can't be interacted with easily or at all by keyboard or by some assistive technologies.
<br><br>
See WCAG section [2.1.1 Keyboard](#keyboard) for further detail.
</td>
</tr>
<tr>
<td>502.3.12 Focus Cursor</td>
<td>Partially supports</td>
<td>
We provide focus styles on all focusable elements. Third party advertising scripts may inject components that remove focus styles.
<br><br>
See WCAG sections [1.4.1 Use of Color](#use-of-color) and [2.4.7 Focus Visible](#focus-visible) for further detail.
</td>
</tr>
<tr>
<td>502.3.13 Modification of Focus Cursor</td>
<td>Supports</td>
<td>The pages of this product use standard HTML elements and cursor controls for user input that may be overriden by assistive technology.</td>
</tr>
<tr>
<td>502.3.14 Event Notification</td>
<td>Partially supports</td>
<td>
The pages of this product use standard HTML and WAI-ARIA attributes to describe the identity, operation, and state of user interface elements to Assistive Technologies.
<br><br>
Some third party scripts may inject content that fails to notify users of changes in state.
<br><br>
See WCAG sections [1.3.1 Info and Relationships](#info-and-relationships) and [4.1.2 Name, Role, Value](#name-role-value) for further detail.
</td>
</tr>
<tr>
<td>502.4 Platform Accessibility Features</td>
<td>Not applicable</td>
<td>This product is not considered platform software as defined by Section 508. See [E103 Definitions, section E103.4](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines#E103-definitions).</td>
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
<td>Not applicable</td>
<td>We do not provide any alternative user interface for this product that functions as assistive technology.</td>
</tr>
<tr>
<td><em><strong>503.4 User Controls for Captions and Audio Description</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>503.4.1 Caption Controls</td>
<td>Not Applicable</td>
<td>Audio and video are not displayed in this product.</td>
</tr>
<tr>
<td>503.4.2 Audio Description Controls</td>
<td>Not Applicable</td>
<td>Audio and video are not displayed in this product.</td>
</tr>
<tr>
<td><em><strong>504 Authoring Tools</strong></em></td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>504.2 Content Creation or Editing (if not authoring tool, enter “not applicable”)</td>
<td>Not applicable</td>
<td>This product is not used as an authoring tool.</td>
</tr>
<tr>
<td>504.2.1 Preservation of Information Provided for Accessibility in Format Conversion</td>
<td>Not applicable</td>
<td></td>
</tr>
<tr>
<td>504.2.2 PDF Export</td>
<td>Not applicable</td>
<td></td>
</tr>
<tr>
<td>504.3 Prompts</td>
<td>Not applicable</td>
<td></td>
</tr>
<tr>
<td>504.4 Templates</td>
<td>Not applicable</td>
<td></td>
</tr>
</tbody>
</table>

### Chapter 6: [Support Documentation and Services](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/draft-rule-2011/chapter-6-documentation-and-support-services)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

## EN 301 549 Report

### Chapter 4: [4.2 Functional Performance Statements](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=22) (FPS)

| **Criteria**                                      | **Conformance Level**    | **Remarks and Explanations** |
| ------------------------------------------------- | ----------------------   | ---------------------------- |
| 4.2.1 Usage without vision                        | Partially supports       | The majority of content is marked up for Assistive Technology. Third party scripts may inject content with inadequate accessible alternatives. |
| 4.2.2 Usage with limited vision                   | Partially supports       | Markup is written with support for assistive technology. Text is resizable by the user. Fonts are set as rems and use pixels as a fallback if not supported. The website does not impede the user from zooming into page. Third party scripts may inject content with inadequate accessible alternatives. |
| 4.2.3 Usage without perception of colour          | Supports                 | Color perception is not needed to use the website. |
| 4.2.4 Usage without hearing                       | Not Applicable	       | Audio is not used in this product. |
| 4.2.5 Usage with limited hearing                  | Not Applicable	       | Audio is not used in this product. |
| 4.2.6 Usage without vocal capability              | Not Applicable	       | Speech is not needed to use this product. |
| 4.2.7 Usage with limited manipulation or strength | Partially supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Fine motor control and simultaneous actions are not required to operate these pages. Third party advertising scripts may inject content that is difficult to use without a pointing device. |
| 4.2.8 Usage with limited reach                    | Partially supports       | This product supports standard input mechanisms such as keyboards, pointing devices, and speech input. Third party advertising scripts may inject content that is difficult to use without a pointing device. |
| 4.2.9 Minimize photosensitive seizure triggers    | Supports                 | The pages of this product do not contain anything that flashes. |
| 4.2.10 Usage with limited cognition               | Partially supports       | The pages of this product have a consistent presentation with clear labels, titles, and accessible names for controls. Third party scripts may inject content with inconsistent or absent labelling of interface components. |
| 4.2.11 Privacy                                    | Supports                 | Standard HTML and WAI-ARIA attributes are used on these pages. The website does not impede the user from using their own privacy tools when interacting with the content. |

### Chapter [5: Generic Requirements](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=23)

Notes: This product supports standard web assistive technologies and is therefore not subject to the Closed Functionality criteria described in this chapter.

### Chapter [6: ICT with Two-Way Voice Communication](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=28) 

Notes: This product does not offer two-way voice communication and is therefore not subject to the requirements of this chapter.

### Chapter [7: ICT with Video Capabilities](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=31) 

Notes: This product does not offer video capabilities and is not subject to the requirements of this chapter.

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
| 11.3.2.4 Assistive technology                                                                     | Not applicable                                                                           | This product is not an assistive technology.                                   |
| 11.3.2.5 Object information                                                                       | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.1 and 502.3.2           | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.1 and 502.3.2 |
| 11.3.2.6 Row, column, and headers                                                                 | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.3                       | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.3             |
| 11.3.2.7 Values                                                                                   | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.4 and 502.3.5           | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.4 and 502.3.5 |
| 11.3.2.8 Label relationships                                                                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.6                       | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.6             |
| 11.3.2.9 Parent-child relationships                                                               | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.7                       | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.7             |
| 11.3.2.10 Text                                                                                    | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.8 and 502.3.9           | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.8 and 502.3.9 |
| 11.3.2.11 List of available actions                                                               | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.10                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.10            |
| 11.3.2.12 Execution of available actions                                                          | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.11                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.11            |
| 11.3.2.13 Tracking of focus and selection attributes                                              | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.12                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.12            |
| 11.3.2.14 Modification of focus and selection attributes                                          | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.13                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.13            |
| 11.3.2.15 Change notification                                                                     | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14            |
| 11.3.2.16 Modifications of states and properties                                                  | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14                      | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.14            |
| 11.3.2.17 Modifications of values and text                                                        | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.5 and 502.3.9           | See [Revised Section 508 Report Ch.5](#chapter-5-software) 502.3.5 and 502.3.9 |
| ***11.4 Documented accessibility usage***                                                         | -                                                                                        | -                                                                              |
| 11.4.1 User control of accessibility features                                                     | Not applicable                                                                           | This product is not considered platform software as defined by EN 301 549 V1.1.2. See [3.1 Definitions](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=18). |
| 11.4.2 No disruption of accessibility features                                                    | Not applicable                                                                           | This product is not considered platform software as defined by EN 301 549 V1.1.2. The product does not impede the user in using accessibility features provided by their operating system and Assistive Technologies. |
| 11.5 User preferences                                                                             | Supports                                                                                 | The pages of this product use standard HTML and CSS attributes that may be overridden in user-supplied style sheets. |
| ***11.6 Authoring tools***                                                                        | -                                                                                        | -                                                                              |
| ***11.6.1 Content technology***                                                                   | -                                                                                        | -                                                                              |
| 11.6.2 Accessible content creation (if not authoring tool, enter “not applicable”)                | Not applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.3 Preservation of accessibility information in transformations                               | Not applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.4 Repair assistance                                                                          | Not applicable                                                                           | This product is not used as an authoring tool.                                 |
| 11.6.5 Templates                                                                                  | Not applicable                                                                           | This product is not used as an authoring tool.                                 |

### Chapter [12: Documentation and Support Services](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=73)

Notes: This report covers accessibility conformance for the web product and does not provide Documentation or Support Services.

### Chapter [13: ICT Providing Relay or Emergency Service Access](http://www.etsi.org/deliver/etsi_en/301500_301599/301549/01.01.02_60/en_301549v010102p.pdf#page=74)

Notes: This product does not provide any relay services, or access for Emergency Services.

## Legal Disclaimer (Springer Nature)

This document is provided for information purposes only and the contents hereof are subject to change without notice. Springer Nature  does not warrant that this document is error free, nor does it provide any other warranties or conditions, whether expressed orally or implied in law, including implied warranties and conditions of merchantability or fitness for a particular purpose. Springer Nature specifically disclaims any liability with respect to this document and no contractual obligations are formed either directly or indirectly by this document. Springer Nature further makes no representation concerning the ability of assistive technologies or other products to interoperate with Springer Nature products. This document addresses the named product(s) or platforms only.
