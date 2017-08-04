# <a name="document-top"></a>Springer Link Voluntary Product Accessibility Template (VPAT)

The data below is valid on the date provided: 4th August 2017.

For more information, contact [onlineservice@springer.com](mailto:onlineservice@springer.com).

<em>The features and explanations provided below are subject to change and updating at Springer Nature's discretion.</em>


## Summary

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| [Section 1194.21 Software Applications and Operating Systems](#section-119421-software-applications-and-operating-systems) |  | |
| [Section 1194.22 Web-based Internet information and applications](#section-119422-web-based-internet-information-and-applications) |  | Our target standards are [https://www.w3.org/TR/WCAG20/](W3C's Web Content Accessibility Guidelines (WCAG) 2.0) (to level AA).<br>We take accessibility very seriously, and are constantly trying to improve. For instance we’ve developed [http://pa11y.org/](pa11y) - a tool that allows automated accessibility testing. We are using this to monitor our accessibility compliance. |
| [Section 1194.23 Telecommunications Products](#section-119423-telecommunications-products)|  | |
| [Section 1194.24 Video and Multi-media Products](#section-119424-video-and-multi-media-products)|  | |
| [Section 1194.25 Self-Contained, Closed Products](#section-119425-self-contained-closed-products)|  | |
| [Section 1194.26 Desktop and Portable Computers](#section-119426-desktop-and-portable-computers)|  | |
| [Section 1194.31 Functional Performance Criteria](#section-119431-functional-performance-criteria) |  |  |
| [Section 1194.41 Information, Documentation and Support](#section-119441-information-documentation-and-support) |  | Documentation and support is available to all users via our FAQ pages or can be provided upon request free of charge. |


## Section 1194.21 Software Applications and Operating Systems

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) When software is designed to run on a system that has a keyboard, product functions shall be executable from a keyboard where the function itself or the result of performing a function can be discerned textually. | Not applicable |  |
| (b) Applications shall not disrupt or disable activated features of other products that are identified as accessibility features, where those features are developed and documented according to industry standards. Applications also shall not disrupt or disable activated features of any operating system that are identified as accessibility features where the application programming interface for those accessibility features has been documented by the manufacturer of the operating system and is available to the product developer. | Not applicable |  |
| (c) A well-defined on-screen indication of the current focus shall be provided that moves among interactive interface elements as the input focus changes. The focus shall be programmatically exposed so that Assistive Technology can track focus and focus changes. | Not applicable |  |
| (d) Sufficient information about a user interface element including the identity, operation and state of the element shall be available to Assistive Technology. When an image represents a program element, the information conveyed by the image must also be available in text. | Not applicable |  |
| (e) When bitmap images are used to identify controls, status indicators, or other programmatic elements, the meaning assigned to those images shall be consistent throughout an application's performance. | Not applicable |  |
| (f) Textual information shall be provided through operating system functions for displaying text. The minimum information that shall be made available is text content, text input caret location, and text attributes. | Not applicable |  |
| (g) Applications shall not override user selected contrast and color selections and other individual display attributes. | Not applicable |  |
| (h) When animation is displayed, the information shall be displayable in at least one non-animated presentation mode at the option of the user. | Not applicable |  |
| (i) Color coding shall not be used as the only means of conveying information, indicating an action, prompting a response, or distinguishing a visual element. | Not applicable |  |
| (j) When a product permits a user to adjust color and contrast settings, a variety of color selections capable of producing a range of contrast levels shall be provided. | Not applicable |  |
| (k) Software shall not use flashing or blinking text, objects, or other elements having a flash or blink frequency greater than 2 Hz and lower than 55 Hz. | Not applicable |  |
| (l) When electronic forms are used, the form shall allow people using Assistive Technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues. | Not applicable |  |

[Return to the top of the document](#document-top)


## Section 1194.22 Web-based Internet information and applications

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) A text equivalent for every non-text element shall be provided (e.g., via “alt”, “longdesc”, or in element content). | Partially supports | Mostly supported, with rare exceptions. Working towards supporting fully. <br>All images provide alternate text or descriptions; background images such as icons on user interface elements contain element content descriptions. <br>Background images are always decorative. |
| (b) Equivalent alternatives for any multimedia presentation shall be synchronized with the presentation. | Does not support | Website allows third parties to provide supplemental material that may be in a multimedia format; equivalent alternatives are encouraged but not required.<br>Currently no method for confirming the inclusion of transcripts or captions. |
| (c) Web pages shall be designed so that all information conveyed with color is also available without color, for example from context or markup. | Supports |  |
| (d) Documents shall be organized so they are readable without requiring an associated style sheet. | Supports |  |
| (e) Redundant text links shall be provided for each active region of a server-side image map. | Not applicable |  |
| (f) Client-side image maps shall be provided instead of server-side image maps except where the regions cannot be defined with an available geometric shape. | Not applicable |  |
| (g) Row and column headers shall be identified for data tables. | Does not support | Working towards supporting.<br>Website does not contain data tables; however, HTML provided by third party may contain data tables without proper markup. |
| (h) Markup shall be used to associate data cells and header cells for data tables that have two or more logical levels of row or column headers. | Does not support | Working towards supporting.<br>HTML provided by third party may contain data tables without proper markup.<br>Efforts are made to encourage proper table markup at the data ingestion stage.<br>We use Pa11y to try and catch specific markup issues and then correct them at source. |
| (i) Frames shall be titled with text that facilitates frame identification and navigation | Partially supports | Third party scripts inject frames without titles. This is not used for anything except advertising. None of the page content is contained within frames. |
| (j) Pages shall be designed to avoid causing the screen to flicker with a frequency greater than 2 Hz and lower than 55 Hz. | Supports |  |
| (k) A text-only page, with equivalent information or functionality, shall be provided to make a web site comply with the provisions of this part, when compliance cannot be accomplished in any other way. The content of the text-only page shall be updated whenever the primary page changes. | Not applicable | We do not provide alternative presentations or alternate pages - instead we ensure that the original page is accessible, which is the better, more accessible solution. I.e. we never have to create a text-only page. |
| (l) When pages utilize scripting languages to display content, or to create interface elements, the information provided by the script shall be identified with functional text that can be read by Assistive Technology. | Partially support | Working towards supporting fully with gradual rollout of redesign.<br>Explicit labels with inputs and Aria roles for interactive user interface elements on redesign.<br>Once the rollout is complete all content will be available via keyboard. |
| (m) When a web page requires that an applet, plug-in or other application be present on the client system to interpret page content, the page must provide a link to a plug-in or applet that complies with §1194.21(a) through (l). | Partially supports | We do not use applets. At this time the only plugins used are to display ads, which we exercise no control over.<br>Where embedded PDFs are used, a fallback to direct file is made available if browser does not have plug in. |
| (n) When electronic forms are designed to be completed on-line, the form shall allow people using Assistive Technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues. | Partially supports | Working towards supporting fully with gradual roll out of redesign, which will have explicit labels with inputs and Aria roles for interactive user interface elements.<br>We use built-in form validation in combination with JavaScript and server side validation that allows specific validation messaging. |
| (o) A method shall be provided that permits users to skip repetitive navigation links. | Partially supports | We provide skip links, which allow our users to skip straight to the content on every page. However we do not provide links that skip every set of navigational links. |
| (p) When a timed response is required, the user shall be alerted and given sufficient time to indicate more time is required. | Not applicable | We do not require timed responses. |

Note to 1194.22: The Board interprets paragraphs (a) through (k) of this section as consistent with the following priority 1 Checkpoints of the Web Content Accessibility Guidelines 1.0 (WCAG 1.0) (May 5 1999) published by the Web Accessibility Initiative of the World Wide Web Consortium: Paragraph (a) - 1.1, (b) - 1.4, (c) - 2.1, (d) - 6.1, (e) - 1.2, (f) - 9.1, (g) - 5.1, (h) - 5.2, (i) - 12.1, (j) - 7.1, (k) - 11.4.

[Return to the top of the document](#document-top)


## Section 1194.23 Telecommunications Products

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) Telecommunications products or systems which provide a function allowing voice communication and which do not themselves provide a TTY functionality shall provide a standard non-acoustic connection point for TTYs. Microphones shall be capable of being turned on and off to allow the user to intermix speech with TTY use. | Not applicable |  |
|(b) Telecommunications products which include voice communication functionality shall support all commonly used cross-manufacturer non-proprietary standard TTY signal protocols. | Not applicable |  |
| (c) Voice mail, auto-attendant, and interactive voice response telecommunications systems shall be usable by TTY users with their TTYs. | Not applicable |  |
| (d) Voice mail, messaging, auto-attendant, and interactive voice response telecommunications systems that require a response from a user within a time interval, shall give an alert when the time interval is about to run out, and shall provide sufficient time for the user to indicate more time is required. | Not applicable |  |
| (e) Where provided, caller identification and similar telecommunications functions shall also be available for users of TTYs, and for users who cannot see displays. | Not applicable |  |
| (f) For transmitted voice signals, telecommunications products shall provide a gain adjustable up to a minimum of 20 dB. For incremental volume control, at least one intermediate step of 12 dB of gain shall be provided. | Not applicable |  |
| (g) If the telecommunications product allows a user to adjust the receive volume, a function shall be provided to automatically reset the volume to the default level after every use. | Not applicable |  |
| (h) Where a telecommunications product delivers output by an audio transducer which is normally held up to the ear, a means for effective magnetic wireless coupling to hearing technologies shall be provided. | Not applicable |  |
| (i) Interference to hearing technologies (including hearing aids, cochlear implants, and assistive listening devices) shall be reduced to the lowest possible level that allows a user of hearing technologies to utilize the telecommunications product. | Not applicable |  |
| (j) Products that transmit or conduct information or communication, shall pass through cross-manufacturer, non-proprietary, industry-standard codes, translation protocols, formats or other information necessary to provide the information or communication in a usable format. Technologies which use encoding, signal compression, format transformation, or similar techniques shall not remove information needed for access or shall restore it upon delivery. | Not applicable |  |
| (k)(1) Products which have mechanically operated controls or keys shall comply with the following: Controls and Keys shall be tactilely discernible without activating the controls or keys. | Not applicable |  |
| (k)(2) Products which have mechanically operated controls or keys shall comply with the following: Controls and Keys shall be operable with one hand and shall not require tight grasping, pinching, twisting of the wrist. The force required to activate controls and keys shall be 5 lbs. (22.2N) maximum. | Not applicable |  |
| (k)(3) Products which have mechanically operated controls or keys shall comply with the following: If key repeat is supported, the delay before repeat shall be adjustable to at least 2 seconds. Key repeat rate shall be adjustable to 2 seconds per character. | Not applicable |  |
| (k)(4) Products which have mechanically operated controls or keys shall comply with the following: The status of all locking or toggle controls or keys shall be visually discernible, and discernible either through touch or sound. | Not applicable |  |

[Return to the top of the document](#document-top)


## Section 1194.24 Video and Multi-media Products

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) All analog television displays 13 inches and larger, and computer equipment that includes analog television receiver or display circuitry, shall be equipped with caption decoder circuitry which appropriately receives, decodes, and displays closed captions from broadcast, cable, videotape, and DVD signals. As soon as practicable, but not later than July 1, 2002, widescreen digital television (DTV) displays measuring at least 7.8 inches vertically, DTV sets with conventional displays measuring at least 13 inches vertically, and stand-alone DTV tuners, whether or not they are marketed with display screens, and computer equipment that includes DTV receiver or display circuitry, shall be equipped with caption decoder circuitry which appropriately receives, decodes, and displays closed captions from broadcast, cable, videotape, and DVD signals. | Not applicable |  |
| (b) Television tuners, including tuner cards for use in computers, shall be equipped with secondary audio program playback circuitry. | Not applicable |  |
| (c) All training and informational video and multimedia productions which support the agency's mission, regardless of format, that contain speech or other audio information necessary for the comprehension of the content, shall be open or closed captioned. | Not applicable |  |
| (d) All training and informational video and multimedia productions which support the agency's mission, regardless of format, that contain visual information necessary for the comprehension of the content, shall be audio described. | Not applicable |  |
| (e) Display or presentation of alternate text presentation or audio descriptions shall be user-selectable unless permanent. | Not applicable |  |

[Return to the top of the document](#document-top)


## Section 1194.25 Self-Contained, Closed Products

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) Self contained products shall be usable by people with disabilities without requiring an end-user to attach Assistive Technology to the product. Personal headsets for private listening are not Assistive Technology. | Not applicable |  |
| (b) When a timed response is required, the user shall be alerted and given sufficient time to indicate more time is required. | Not applicable |  |
| (c) Where a product utilizes touchscreens or contact-sensitive controls, an input method shall be provided that complies with §1194.23 (k) (1) through (4). | Not applicable |  |
| (d) When biometric forms of user identification or control are used, an alternative form of identification or activation, which does not require the user to possess particular biological characteristics, shall also be provided. | Not applicable |  |
| (e) When products provide auditory output, the audio signal shall be provided at a standard signal level through an industry standard connector that will allow for private listening. The product must provide the ability to interrupt, pause, and restart the audio at anytime. | Not applicable |  |
| (f) When products deliver voice output in a public area, incremental volume control shall be provided with output amplification up to a level of at least 65 dB. Where the ambient noise level of the environment is above 45 dB, a volume gain of at least 20 dB above the ambient level shall be user selectable. A function shall be provided to automatically reset the volume to the default level after every use. | Not applicable |  |
| (g) Color coding shall not be used as the only means of conveying information, indicating an action, prompting a response, or distinguishing a visual element. | Not applicable |  |
| (h) When a product permits a user to adjust color and contrast settings, a range of color selections capable of producing a variety of contrast levels shall be provided. | Not applicable |  |
| (i) Products shall be designed to avoid causing the screen to flicker with a frequency greater than 2 Hz and lower than 55 Hz. | Not applicable |  |
| (j) (1) Products which are freestanding, non-portable, and intended to be used in one location and which have operable controls shall comply with the following: The position of any operable control shall be determined with respect to a vertical plane, which is 48 inches in length, centered on the operable control, and at the maximum protrusion of the product within the 48 inch length on products which are freestanding, non-portable, and intended to be used in one location and which have operable controls. | Not applicable |  |
| (j)(2) Products which are freestanding, non-portable, and intended to be used in one location and which have operable controls shall comply with the following: Where any operable control is 10 inches or less behind the reference plane, the height shall be 54 inches maximum and 15 inches minimum above the floor. | Not applicable |  |
| (j)(3) Products which are freestanding, non-portable, and intended to be used in one location and which have operable controls shall comply with the following: Where any operable control is more than 10 inches and not more than 24 inches behind the reference plane, the height shall be 46 inches maximum and 15 inches minimum above the floor. | Not applicable |  |
| (j)(4) Products which are freestanding, non-portable, and intended to be used in one location and which have operable controls shall comply with the following: Operable controls shall not be more than 24 inches behind the reference plane. | Not applicable |  |

[Return to the top of the document](#document-top)


## Section 1194.26 Desktop and Portable Computers

| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) All mechanically operated controls and keys shall comply with §1194.23 (k) (1) through (4). |  Not applicable|  |
| (b) If a product utilizes touchscreens or touch-operated controls, an input method shall be provided that complies with §1194.23 (k) (1) through (4). | Not applicable |  |
| (c) When biometric forms of user identification or control are used, an alternative form of identification or activation, which does not require the user to possess particular biological characteristics, shall also be provided. | Not applicable |  |
| (d) Where provided, at least one of each type of expansion slots, ports and connectors shall comply with publicly available industry standards | Not applicable |  |

[Return to the top of the document](#document-top)


## Section 1194.31 Functional Performance Criteria
| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) At least one mode of operation and information retrieval that does not require user vision shall be provided, or support for Assistive Technology used by people who are blind or visually impaired shall be provided. | Partially supports | Majority of content is marked up for Assistive Technology.<br>Currently third­-party scripts are used to provide related article content ­ this requires a mouse (specifically the visual representation used to link articles relatedness). However a list alternative is provided beside it.<br>This has been redesigned on the new article page so that it does not have a dependency on using a mouse.<br>"Look Inside" feature that shows preview content to users with no access has been removed on redesign where HTML is provided instead.<br>However still present on old sites that have yet to be reached by ongoing redesign. |
| (b) At least one mode of operation and information retrieval that does not require visual acuity greater than 20/70 shall be provided in audio and enlarged print output working together or independently, or support for Assistive Technology used by people who are visually impaired shall be provided. | Supports |  |
| (c) At least one mode of operation and information retrieval that does not require user hearing shall be provided, or support for Assistive Technology used by people who are deaf or hard of hearing shall be provided | Partially supports | The majority of our content is text based.<br>Supplemental material provided by third-parties may contain audio files without transcript. |
| (d) Where audio information is important for the use of a product, at least one mode of operation and information retrieval shall be provided in an enhanced auditory fashion, or support for assistive hearing devices shall be provided. | Not applicable |  |
| (e) At least one mode of operation and information retrieval that does not require user speech shall be provided, or support for Assistive Technology used by people with disabilities shall be provided. | Not applicable |  |
| (f) At least one mode of operation and information retrieval that does not require fine motor control or simultaneous actions and that is operable with limited reach and strength shall be provided. | Partially supports | The majority of content is accessible via keyboard. Mouse interactions necessary for some features.<br>Exceptions are listed above in section 1194.31(a). |

[Return to the top of the document](#document-top)


## Section 1194.41 Information, Documentation and Support
| Criteria | Supporting features | Remarks and explanations |
| -------- | ------------------- | ------------------------ |
| (a) Product support documentation provided to end-users shall be made available in alternate formats upon request, at no additional charge | Supports | Information available on the website via FAQ page and additional information can be requested for free by contacting support. |
| (b) End-users shall have access to a description of the accessibility and compatibility features of products in alternate formats or alternate methods upon request, at no additional charge. | Supports | Additional information available on [the website's accessibility page](https://link.springer.com/accessibility) - linked to from the footer of the website.<br>More information can be provided upon request. |
| (c) Support services for products shall accommodate the communication needs of end-users with disabilities. | Supports | The page outlining our approach to accessibility can be read by assistive technologies.  Additional information can be requested via email, telephone or post. Details of contact information can be found on the [contact us page](https://link.springer.com/contactus). |

[Return to the top of the document](#document-top)

