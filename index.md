---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "3DAROC22 - 3C-based data analysis and 3D reconstruction of chromatin folding"
  description: "3C-based methods, such as Hi-C, produce a huge amount of raw data as pairs of DNA reads that are in close spatial proximity in the cell nucleus. Overall, those interaction matrices have been used to study how the genome folds within the nucleus, which is one of the most fascinating problems in modern biology. The rigorous analysis of those paired-reads using computational tools has been essential to fully exploit the experimental technique, and to study how the genome is folded in space. Currently, there is a clear expansion on the wealth of data on genome structure with the availability of many datasets of Hi-C experiments down to 1Kb resolution (see for example:
http://hic.umassmed.edu/welcome/welcome.php or http://www.aidenlab.org/data.html)."

  # Keywords -> Consult EDAM:Topic
  keywords:  ""

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "CO-AUTHOR_1"
    - "@type": Person
      name: "CO-AUTHOR_2"
    - "@type": Person
      name: "CO-AUTHOR_3"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/Web_course_template/"
---

# 3DAROC22 - 3C-based data analysis and 3D reconstruction of chromatin folding

![3DAROC22](/assets/3DAROC22.png)


## Course Description
3C-based methods, such as Hi-C, produce a huge amount of raw data as pairs of DNA reads that are in close spatial proximity in the cell nucleus. Overall, those interaction matrices have been used to study how the genome folds within the nucleus, which is one of the most fascinating problems in modern biology. The rigorous analysis of those paired-reads using computational tools has been essential to fully exploit the experimental technique, and to study how the genome is folded in space. Currently, there is a clear expansion on the wealth of data on genome structure with the availability of many datasets of Hi-C experiments down to 1Kb resolution (see for example:
http://hic.umassmed.edu/welcome/welcome.php or http://www.aidenlab.org/data.html).

## Target Audience
The course design is oriented towards experimental researchers and bioinformaticians at the graduate and post-graduate levels. The last edition of this course was attended by people with different backgrounds and interested in the genome organization. It is likely that the participants to this course aim at getting involved in generating Hi-C data for chromosome structure determination or that they just want to be able to correctly interpret and analyse publicly available data.

## Detailed Program

<table>
  <tbody>
    <tr>
      <th>Days</th>
      <th>Lectures (pdf)</th>
      <th>Core pipeline (notebooks)</th>
    </tr>
    <tr>
     <td><strong>Day 1</strong></td>
     <td>
       <ul>
        <li> <a href="./assets/Presentations/Day1/20221122_01_Welcome.pdf">Welcome and introduction</a></li>
        <li> <a href="./assets/Presentations/Day1/20221122_02_overview_on_structure_determination.pdf">Overview on structure determination</a></li>
        <li> <a href="./assets/Presentations/Day1/20221122_03_3D_Genomics.pdf">Overview of 3D genomes</a></li>
        <li> <a href="./assets/Presentations/Day1/20221122_04_Introduction_to_linux.pdf">Live Introduction to Linux and working environment</a></li>
        <li> <a href="./assets/Presentations/Day1/20221122_05_Intro_TADbit.pdf">Introduction to TADbit and data handling for 3C-based experiments</a></li>
        <li> <a href="./assets/Presentations/Day1/20221122_06_NGS_for_HiC.pdf">From raw data to Hi-C contact matrices</a></li>
       </ul>
     </td>
     <td>
<ul>
        <li> <a href="./assets/Notebooks/01-Inspect_Hi-C_input_data.ipynb">01-Inspect_Hi-C_input_data.ipynb</a></li>
    <li> <a href="./assets/Notebooks/02-Generate_mapper_index.ipynb">02-Generate_mapper_index.ipynb</a></li>
    <li> <a href="./assets/Notebooks/03-Hi-C_Quality_Check.ipynb">03-Hi-C_Quality_Check.ipynb</a></li>
    <li> <a href="./assets/Notebooks/04-Mapping.ipynb">04-Mapping.ipynb</a></li>
    <li> <a href="./assets/Notebooks/05-Parsing.ipynb">05-Parsing.ipynb</a></li>
</ul>
    </td>
   </tr>
    <tr>
     <td><strong>Day 2</strong></td>
     <td>
       <ul>
        <li> <a href="./assets/Presentations/Day2/20221123_01_Chromatin_and_3Cs.pdf">Chromatin structure and 3C data</a></li>
        <li> <a href="./assets/Presentations/Day2/20221123_02_Integrative_modelling_applied_to_chromatin.pdf">Integrative modeling applied to chromatin with TADbit</a></li>
        <li> <a href="./assets/Presentations/Day2/20221123_04_Hi-C_contact_matrices_filtering.pdf">Hi-C contact matrices: filtering</a></li>
        <li> <a href="./assets/Presentations/Day2/20221123_01_Applications(I)_SOX2Dynamics.pdf">Biological applications I: SOX2 gene activation dynamics)</a></li>
       </ul>
     </td>
     <td>
     <ul>
             <li> <a href="./assets/Notebooks/06-Intersecting_and_Filtering_mapped_reads.ipynb">06-Intersecting_and_Filtering_mapped_reads.ipynb</a></li>
         <li> <a href="./assets/Notebooks/07-Bin_filtering_and_normalization.ipynb">07-Bin_filtering_and_normalization.ipynb</a></li>
         <li> <a href="./assets/Notebooks/Higlass.ipynb">Higlass.ipynb</a></li>
     </ul>
    </td>
   </tr>
   <tr>
    <td><strong>Day 3</strong></td>
    <td>
      <ul>
       <li> <a href="./assets/Presentations/Day3/20221124_Applications(II)_CHROMATIC.pdf">Biological Application - CHROMATIC</a></li>
       <li> <a href="./assets/Presentations/Day3/20221124_Comparison_between_experiments.pdf">Comparison between experiments</a></li>
      </ul>
    </td>
    <td>
    <ul>
            <li> <a href="./assets/Notebooks/08-Compartments_and_TADs_detection.ipynb">08-Compartments_and_TADs_detection.ipynb</a></li>
        <li> <a href="./assets/Notebooks/08b-insulation_score.ipynb">08b-insulation_score.ipynb</a></li>
        <li> <a href="./assets/Notebooks/09-Compare_and_merge_Hi-C_experiments.ipynb">09-Compare_and_merge_Hi-C_experiments.ipynb</a></li>
        <li> <a href="./assets/Notebooks/09b_CHESS_Compare_chromatin_contact_data.ipynb">09b_CHESS_Compare_chromatin_contact_data.ipynb</a></li>

    </ul>
   </td>
  </tr>

  </tbody>
</table>

### Learning objectives

In this course, participants will learn to use __TADbit tools__, a wraper to the TADbit python library designed and developed to manage all the dimensionalities of the Hi-C data. Compared to previous 3DAROC courses, this course we will lower the learning curve and provide means to analyze 3C-based data using only command tools. So, if you know how run a command line in linux, you can learn and use TADbit tools. The tutorials will evolve around:

 - 1D - Map paired-end sequences to generate Hi-C interaction matrices
 - 2D - Normalize matrices and identify constitutive domains (compartments, TADs)
 - 3D - Generate populations of model structures which reproduce the Hi-C interaction matrices
 - 4D - Compare samples at different time points

Participants can bring specific biological questions and/or their own 3C data to analyze during the course. At the end of the course, participants will be familiar with the TADbit tools software, and will be able to fully analyze Hi-C data.

*__Note__: Although the TADbit software is central in this course, alternative software will be discussed for each part of the analysis.*

### Instructors
Marc A. Martí-Renom obtained a PhD in Biophysics from the Universidad Autonoma de Barcelona (UAB) where he worked on protein folding under the supervision of B. Oliva, F.X. Aviles and M. Karplus (Nobel Laureate for Chemistry 2013). After that, he went to the US for a postdoctoral training on protein structure modelling at the Sali Lab (Rockefeller University) as the recipient of the Burroughs Wellcome Fund fellowship. Later on, Marc was appointed Assistant Adjunct Professor at UCSF. Between 2006 and 2011, he headed the Structural Genomics Group at the CIPF in Valencia (Spain). Currently, Marc is an ICREA research professor and leads the Structural Genomics Group at the National Center for Genomic Analysis - Centre for Genomic Regulation (CNAG-CRG) in Barcelona. His research group employs the laws of physics and the rules of evolution to develop and apply experimental and computational methods for elucidating the 3D structures of macromolecules and their complexes. Between 2012 and 2018, Marc was an Associate Editor of the PLoS Computational Biology journal and has published over 120 articles in international peer-reviewed journals. He coordinated two international teams funded by the EU (Era-Net Pathogenomics Grant) and the HFSP (Research Grants Award). Since 2014, he became the co-PI on the 4DGenome Grant funded by the ERC Synergy program as well as the co-PI on the MuG Research project funded by the European Commission H2020 program. In the last few years, Marc played a key role in Europe to promote the 4DNucleome Initiative, which recently joined forces with the single-cell and organoid communities to form the LifeTime Initiative towards a FET-FLAGSHIP in Europe to which he is a Steering Committee Member. Marc collaborates in GTPB as an instructor since 2008. PGDD08 - Pharmacogenomics: new opportunities for drug discovery; SG09 - Structural Genomics; SGDD10 - Structural Genomics and Drug Design; CSDM14-Chromosome structure determination using modelling and Hi-C data; 3DAROC16 - 3C-based data analysis and 3D reconstruction of chromatin folding; 3DAROC16, 3DAROC18 and 3DAROC21 - 3C-based data analysis and 3D reconstruction of chromatin folding.

https://orcid.org/0000-0002-0151-4279

Marco Di Stefano obtained his Ph.D. in Biophysics in 2014 (Scuola Internazionale Superiore di Studi Avanzati: Trieste, Friuli-Venezia Giulia, IT) working on Physics-based structural models of chromosomes to study the relationship between gene co-expression and gene co-localization. He moved as a post-doctoral researcher to the structural genomics group of Marc Marti-Renom at CNAG-CRG (Barcelona). His main research interest is in integrating chromosome conformation capture data, epigenomics, and polymer Physics to study constitutive mechanisms of chromosome folding. He has been involved in GTPB as an instructor for 3DAROC16 and 3DAROC21- 3C-based data analysis and 3D reconstruction of chromatin folding.
In October 2020 he moved to the Institute of Human Genetics (Montpellier, FR) as a senior post-doc in the Chromatin and Cell Biology group led by Giacomo Cavalli. He is extending his studies on the relationship between epigenetics, gene expression, and genome structural organization and dynamics.

https://orcid.org/0000-0001-6195-4754

David Castillo obtained his MSc in Photonics from the Universitat PolitÃ¨cnica de Catalunya in Barcelona (Spain) where he worked in Super-resolution microscopy. He has a background in Physics and Engineering. He works as a technician in the Structural Genomics team of Marc A. MartÃ­-Renom at CNAG-CRG (Barcelona), developing tools for the analysis, modelling and visualization of Hi-C data. David is also interested in the integration of microscopy into the modeling of genomic 3D structures.He has been involved in GTPB as an instructor for 3DAROC18 - 3C-based data analysis and 3D reconstruction of chromatin folding.

---

The source for this course webpage is [in github](https://github.com/GTPB/3DAROC22).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Web_course_template</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
