---
# === Required fields  ===
# Your name 
name: "Jiawei Chen"
# Your profile picture
imgname: 
  name: "img/jiawei.jpg"
  alt: "Picture of me"
  type: image/jpeg
# More sources can be added (optional) using 
# imgOther:
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
# ...
# A title (job title or "Researcher", "PhD student", etc.)
personal_title: "Robotics PhD Candidate"
# An address (you can list multiple)
address: 
  - 
    name: University of Michigan
    locality: Ann Arbor, MI, USA
    email: chenjw [at] umich (dot) edu
    googlescholar: "https://scholar.google.com/citations?user=qrIktewAAAAJ"
    twitter: jchenrobotics
    linkedin: "https://www.linkedin.com/in/jiawei-chen-robotics/"
    github: jchen-cs
    cv: "Chen_Jiawei_CV_23May.pdf"

# === Optional fields ===
# Add an email with a mailto: hyperlink
# email: aaaa@example.com
# Add an email "image" for spam protection. With light and dark mode
# emailImg: 
#   dark: /img/dark_email.png
#   light: /img/light_email.png

# List your publications. The required fields are pdf, title, and image 
# (which should be the image path). The other fields are optional.
publications:
  -
    authors:
      - name: Brown, G. M.
      - name: Chen, J.
        me: true
      - name: Fudickar, A. M.
      - name: Jahn, A. E.
    title: "An Open-Source Platform for Sub-g, Sub-µA Data Loggers"
    date: 2023
    journal: Animal Biotelemetry
    image: img/abit23.jpeg
    citation: "@article{brown_open-source_2023,
	title = {An open-source platform for sub-$${\\textbackslash}textrm{g}$$, sub-$${\\textbackslash}upmu$${A} data loggers},
	volume = {11},
	issn = {2050-3385},
	url = {https://animalbiotelemetry.biomedcentral.com/articles/10.1186/s40317-023-00327-0},
	doi = {10.1186/s40317-023-00327-0},
	abstract = {Background  Rapid improvements in inexpensive, low-power, movement and environmental sensors have sparked a revolution in animal behavior research by enabling the creation of data loggers (henceforth, tags) that can capture fine-grained behavioral data over many months. Nevertheless, development of tags that are suitable for use with small species, for example, birds under 25 g, remains challenging because of the extreme mass (under 1 g ) and power (average current under 1µ   A) constraints. These constraints dictate that a tag should carry exactly the sensors required for a given experiment and the data collection protocol should be specialized to the experiment. Furthermore, it can be extremely challenging to design hardware and software to achieve the energy efficiency required for long tag life. Results  We present an activity monitor, BitTag, that can continuously collect activity data for 4–12 months at 0.5–0.8g , depending upon battery choice, and which has been used to collect more than 500,000 h of data in a variety of experiments. The BitTag architecture provides a general platform to support the development and deployment of custom sub-g tags. This platform consists of a flexible tag architecture, software for both tags and host computers, and hardware to provide the host/tag interface necessary for preparing tags for “flight” and for accessing tag data “postflight”. We demonstrate how the BitTag platform can be extended to quickly develop novel tags with other sensors while satisfying the 1g/1µ A mass and power requirements through the design of a novel barometric pressure sensing tag that can collect pressure and temperature data every 60s for a year with mass under 0.6g.},
	language = {en},
	number = {1},
	urldate = {2023-05-08},
	journal = {Animal Biotelemetry},
	author = {Brown, Geoffrey M. and Chen, Jiawei and Fudickar, Adam and Jahn, Alex E.},
	month = may,
	year = {2023},
	pages = {19},
}
"
    pdf: papers/abit23.pdf
    links:
      -
        name: Link
        url: "https://animalbiotelemetry.biomedcentral.com/articles/10.1186/s40317-023-00327-0#author-information"
  -
    authors:
      - name: Chen, J.
        me: true
      - name: Vargas de Mendonça, J. L. 
      - name: Jalili, S. 
      - name: Ayele, B.
      - name: Bekele, B.
      - name: Qu, Z.
      - name: Sharma, P.
      - name: Shiferaw, T.
      - name: Zhang, Y.
      - name: Jeannin, J-B.
    title: "Synchronous Programming and Refinement Types in Robotics: From Verification to Implementation"
    date: 2022
    journal: Formal Techniques in Safety-Critical Systems (FTSCS)
    image: img/ftscs22.jpg
    citation: "@inproceedings{chen2022synchronous,
	address = {New York, NY, USA},
	series = {{FTSCS} 2022},
	title = {Synchronous {Programming} and {Refinement} {Types} in {Robotics}: {From} {Verification} to {Implementation}},
	copyright = {All rights reserved},
	isbn = {978-1-4503-9907-4},
	shorttitle = {Synchronous {Programming} and {Refinement} {Types} in {Robotics}},
	url = {https://doi.org/10.1145/3563822.3568015},
	doi = {10.1145/3563822.3568015},
	abstract = {Robots and other cyber-physical systems are held to high standards of safety and reliability, and thus one must be confident in the correctness of their software. Formal verification can provide such confidence, but programming languages that lend themselves well to verification often do not produce executable code, and languages that are executable do not typically have precise enough formal semantics. We present MARVeLus, a stream-based approach to combining verification and execution in a synchronous programming language that allows formal guarantees to be made about implementation-level source code. We then demonstrate the end-to-end process of developing a safe robotics application, from modeling and verification to implementation and execution.},
	urldate = {2023-02-27},
	booktitle = {Proceedings of the 8th {ACM} {SIGPLAN} {International} {Workshop} on {Formal} {Techniques} for {Safety}-{Critical} {Systems}},
	publisher = {Association for Computing Machinery},
	author = {Chen, Jiawei and Vargas de Mendonça, José Luiz and Jalili, Shayan and Ayele, Bereket and Bekele, Bereket Ngussie and Qu, Zhemin and Sharma, Pranjal and Shiferaw, Tigist and Zhang, Yicheng and Jeannin, Jean-Baptiste},
	month = dec,
	year = {2022},
	keywords = {refinement types, cyber-physical systems, formal verification, robotics, synchronous programming},
	pages = {68--79},
}"
    pdf: papers/ftscs22.pdf
    links:
      -
        name: Link
        url: "https://dl.acm.org/doi/10.1145/3563822.3568015"

  -
    authors:
      - name: Jeannin, J-B.
      - name: Chen, J.
        me: true
      - name: Vargas de Mendonça, J. L.
      - name: Mamouras, K.
    title: "Work-in-Progress: Towards a Theory of Robust Quantitative Semantics for Signal Temporal Logic"
    date: 2022
    journal: International Conference on Embedded Software (EMSOFT)
    image: img/emsoft22.png
    citation: "
@inproceedings{jeannin2022work--progress,
	title = {Work-in-{Progress}: {Towards} a {Theory} of {Robust} {Quantitative} {Semantics} for {Signal} {Temporal} {Logic}},
	shorttitle = {Work-in-{Progress}},
	doi = {10.1109/EMSOFT55006.2022.00013},
	abstract = {Several quantitative semantics of temporal logics have been investigated recently. We propose a general form to model those quantitative semantics, establish requirements for soundness, and evaluate the framework on a few examples.},
	booktitle = {2022 {International} {Conference} on {Embedded} {Software} ({EMSOFT})},
	author = {Jeannin, Jean-Baptiste and Chen, Jiawei and de Mendonça, José Luiz Vargas and Mamouras, Konstantinos},
	month = oct,
	year = {2022},
	note = {ISSN: 2771-571X},
	keywords = {Embedded software, Quantitative Semantics, Semantics, Signal temporal logic},
	pages = {11--12},
}
"
    pdf: papers/emsoft22.pdf
    links:
      -
        name: Link
        url: "https://ieeexplore.ieee.org/abstract/document/9934953"

  -
    authors:
      - name: Chen, J.
        me: true
      - name: Brown, G.
      - name: Fudickar, A.
    title: Simulation-Based Validation of Activity Logger Data for Animal Behavior Studies
    date: 2021
    journal: Animal Biotelemetry
    image: img/abit21.jpg
    citation: "
@article{chen2021simulation-based,
	title = {Simulation-based validation of activity logger data for animal behavior studies},
	volume = {9},
	copyright = {All rights reserved},
	issn = {2050-3385},
	url = {https://animalbiotelemetry.biomedcentral.com/articles/10.1186/s40317-021-00254-y},
	doi = {10.1186/s40317-021-00254-y},
	abstract = {Bio-loggers are widely used for studying the movement and behavior of animals. However, some sensors provide more data than is practical to store given experiment or bio-logger design constraints. One approach for overcoming this limitation is to utilize data collection strategies, such as non-continuous recording or data summarization that may record data more efficiently, but need to be validated for correctness. In this paper we address two fundamental questions—how can researchers determine suitable parameters and behaviors for bio-logger sensors, and how do they validate their choices? We present a methodology that uses software-based simulation of bio-loggers to validate various data collection strategies using recorded data and synchronized, annotated video. The use of simulation allows for fast and repeatable tests, which facilitates the validation of data collection methods as well as the configuration of bio-loggers in preparation for experiments. We demonstrate this methodology using accelerometer loggers for recording the activity of the small songbird Junco hyemalis hyemalis.},
	language = {en},
	number = {1},
	urldate = {2021-09-13},
	journal = {Animal Biotelemetry},
	author = {Chen, Jiawei and Brown, Geoffrey and Fudickar, Adam},
	month = dec,
	year = {2021},
	pages = {31},
}
"
    pdf: papers/abit21.pdf
    links:
      -
        name: Link
        url: "https://animalbiotelemetry.biomedcentral.com/articles/10.1186/s40317-021-00254-y"

---

# About Me
I’m a third-year Robotics PhD Candidate at the University of Michigan, advised by [Jean-Baptiste Jeannin](https://jeannin.github.io) in the [MARVL](https://marvl.engin.umich.edu) group. My research revolves around [designing more reliable embedded systems](/research), whether they are roving around on wheels, thrusted by propellers, or worn by migratory birds. Recently, my interest has been in applying formal methods to robotics and robotics-adjacent applications. Outside of research, I enjoy growing unique and interesting houseplants, playing the piano, and volunteering at robotics competitions. I have also designed and built a small fleet of remote-controlled aircraft, and currently maintain an electronics prototyping lab. 


## Education

* **[in-progress] Robotics PhD** University of Michigan, advised by Jean-Baptiste Jeannin, 2020-present
* **Robotics MS** University of Michigan, 2020-2022
* **Computer Science + Physics BA** Indiana University Bloomington, 2016-2020
    - Mathematics Minor
    - Graduated with Highest Distinction, Hutton Honors Notation, and Computer Science Departmental Honors 
