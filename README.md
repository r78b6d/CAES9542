java c
CAES9542 Technical English for Computer Science 2024-25
Cohesion Homework
OverviewIn addition to using appropriate evaluative language, the quality of your justification also depends on how clearly and cohesively you write.  There is a common belief that technical information must be phrased in long and complex sentence structures. This is not exactly true because overly complex sentences and convoluted ideas will unduly confuse readers.
TASK 1 - Evaluate the readability of a short technical descriptionRead an adapted version of a short paragraph on extracting example code and examples by an online tool Blueprint (Blueprint is a tool that integrates Web search into a development environment). Is it easy to understand?
Text 1 [1]
Blueprint locates and extracts source code from web pages by segmenting them and the segments of which are then classified based on their being source code or not, which represents an online process taking the current Blueprint prototype about 10 seconds per page.
Rewrite the paragraph to improve its clarity. Hints:
•   Avoid using “which”
•   Think of how many steps Blueprint uses to complete the locating and extracting the source code. What linking words can you use to list these?
•   Divide the paragraph into 2 or three sentences.
Put your rewrite her
Additional pointers are provided below for improving clarityIn writing technical document, one thing that writers need to bear in mind is that readers of your text would not like to spend time on decoding every sentence. It is therefore important to take readability into serious consideration when explaining technical information.Make your sentence straightforward and concise:• Simplify your sentence to focus on one idea with a clear subject and succinct verb• Avoid sentences with this topical structure “For xxx, it is…”• e.g., For the Code of Practice for Fire Resisting Construction, it requires that every building should be divided into compartments to inhabit the spread the fire.• Simply say “The Code of Practice for Fire Resisting Construction requires that …”
Maintaining cohesion can greatly enhance readability of a textSection overviews are helpful to the reader, particularly for longer documents such as FYP reports. They give an overview of content, tell the reader what to expect, and allow the reader to skip to subsections if they want.
TASK 2 - Cohesion at the Section / Chapter levelThe extract below is from a  student FYP entitled “ Validation of the diagnostic accuracy of computational high-throughput autofluorescence microscopy by pattern illumination (CHAMP) for subtyping lung adenocarcinoma.”
There are two versions of the extract. Read Version A first and then Version B of the extract. As a reader which version do you prefer and why?
Text 2 [2]
Version A
2 Methodology
2.1 Collection of biological tissues
The lung tumour tissues used in this study were acquired from lung tumour removal surgical patients at the Hong Kong Queen Mary Hospital. The tissues were taken from the resected lung lobes using a scalpel and then fixed for a day at room temperature in 4% neutral-buffered formalin before being transferred to the HKUST TAB-Lab for imaging. All human-related experiments were conducted in compliance with the Institutional Review Board of the University of Hong Kong/ Hospital Authority Hong Kong West Cluster (HKU/HA HKW) with reference number UW 20–335. Consent for tissue usage was also secured from all lung cancer tissue donors.
2.2 CHAMP imaging of human lung tumour tissue slices
The tissues fixed in formalin were subjected to dehydration, before being cleared and impregnated using a tissue processor. This processing took approximately 12 hours before the samples were embedded into paraffin. As validation of CHAMP images was to be carried out on thin tissue slices for fair comparisons to histological stained images, the paraffin-embedded block specimens were sliced to a thickness of 7µm using a RM2235 Leica Inc. microtome and mounted on quartz slides. For CHAMP imaging, quartz slides were preferred due to their high UV transparency, as conventional glass slides would absorb the UV rays, resulting in low image contrast of the sample.
[Text removed]
2.3 Histological imaging of human lung tumour tissue slices
Once CHAMP imaging was completed, the tissues were subjected to standard histological procedures to acquire the HE reference images. Firstly, the quartz coverslip was removed by placing the sample in the water and gently waving it. The sample was then stained with HE and cover slipped after drying. The stained thin tissue slices were imaged by Hamamatsu Photonic K.K's NanoZoomer-SQ to produce histological images. Histological software, ImageJ, was subsequently used to view fine histological details of the sample.
2.4 Validation of elastic fibres as a diagnostic tool using image processing
Elastin van Gieson (EVG) staining is a common method used for distinguishing elastin fibres in connective tissue. CHAMP was validated for the visualization of elastin fibres in lung adenocarcinoma samples through visual comparison with previously archived EVG-stained lung adenocarcinoma samples.
In the image processing phase, pixels representing elastic fibres from CHAMP images were extracted using Python code. The code was implemented using the following Python packages: OpenCV, NumPy, and PIL. CHAMP images are first read into the code using the image path.
Version B
2 Met代 写CAES9542 Technical English for Computer Science 2024-25Python
代做程序编程语言hodology
There were four main stages to performing imaging of human lung tumour tissue which involved collecting biological tissues (Section 2.1), CHAMP imaging of human lung tumour tissue slices (Section 2.2), imaging of the tissue slices using a microscope (Section 2.3), and validation of elastin fibres in the lung as a diagnostic tool using image processing (Section 2.4). These are described in more detail below.
2.1 Collection of biological tissues
The lung tumour tissues used in this study were acquired from lung tumour removal surgical patients at the Hong Kong Queen Mary Hospital. The tissues were taken from the resected lung lobes using a scalpel and then fixed for a day at room temperature in 4% neutral-buffered formalin before being transferred to the HKUST TAB-Lab for imaging. All human-related experiments were conducted in compliance with the Institutional Review Board of the University of Hong Kong/ Hospital Authority Hong Kong West Cluster (HKU/HA HKW) with reference number UW 20–335. Consent for tissue usage was also secured from all lung cancer tissue donors.
2.2 CHAMP imaging of human lung tumour tissue slices
The tissues fixed in formalin were subjected to dehydration, before being cleared and impregnated using a tissue processor. This processing took approximately 12 hours before the samples were embedded into paraffin. As validation of CHAMP images was to be carried out on thin tissue slices for fair comparisons to histological stained images, the paraffin-embedded block specimens were sliced to a thickness of 7µm using a RM2235 Leica Inc. microtome and mounted on quartz slides. For CHAMP imaging, quartz slides were preferred due to their high UV transparency, as conventional glass slides would absorb the UV rays, resulting in low image contrast of the sample.
[Text removed]
2.3 Histological imaging of human lung tumour tissue slices
Once CHAMP imaging was completed, the tissues were subjected to standard histological procedures to acquire the HE reference images. Firstly, the quartz coverslip was removed by placing the sample in the water and gently waving it. The sample was then stained with HE and cover slipped after drying. The stained thin tissue slices were imaged by Hamamatsu Photonic K.K's NanoZoomer-SQ to produce histological images. Histological software, ImageJ, was subsequently used to view fine histological details of the sample.
2.4 Validation of elastic fibres as a diagnostic tool using image processing
Elastin van Gieson (EVG) staining is a common method used for distinguishing elastin fibres in connective tissue. CHAMP was validated for the visualization of elastin fibres in lung adenocarcinoma samples through visual comparison with previously archived EVG-stained lung adenocarcinoma samples.
In the image processing phase, pixels representing elastic fibres from CHAMP images were extracted using Python code
1.   For CAES9542, we want you to give a short overview only for the main body sections / chapters e.g., Methodology / Design, Results and Discussion
2.   If these main sections do not have subsections (e.g., Introduction, Conclusion) there is no need to have a section overview.
3.   If you have subsections within subsections e.g., 3.1.1, 3.1.2 there is no need to have a section overview.
4. When submitting your FYP report to your supervisor you can ask them whether they want you to give a section overview for all sections and subsections.
TASK 3 - Identify cohesive devices
Look at the following comments on a longer section of extracting example code and examples by Blueprint and see how the cohesion is achieved through different cohesive devices.
Find examples in the text of the different types of cohesion listed below:
•     Referencing device (referring back to previous concepts, ideas, processes)
•     Sequential
•     Cause and effect
•     Conditional (something has to happen first before something else happens)
One example has been done for you.
Text 3 [1]
Text
Cohesive devices
To facilitate locating and extracting source code from Web pages, Blueprint first segments the page. Then, Blueprint classifies each segment as being source code or not.   This offline processing takes the current Blueprint prototype about 10 seconds per page.Since HTML documents often contain errors (e.g., missing tags or extraneous quotes), Blueprint first transforms them into proper XHTML documents so that we can leverage their structure in the segmentation process.   We pre-process  the HTML file with the Beautiful Soup library, which generates valid XHTML output for any input.
Next Blueprint divides the resulting hierarchical XHTML document  into  independent  segments by  examining block- level elements. Blueprint uses 31 tags to define blocks; the most common are: P, H1, DIV, and PRE.   We also extract SCRIPT. and   OBJECT   blocks   as   block-level   elements, because running examples are usually contained within these tags.   To  find block-level elements, Blueprint traverses the document depth-first.   When  we  reach  a leaf element,  we backtrack to the nearest containing block-level element and create a segment.   If the root  of the tree  is  reached before finding a block-level element, the element immediately before the root  is  extracted  as  a  segment.    This  algorithm keeps segments ordered exactly as they were in the original document.


Sequential



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
