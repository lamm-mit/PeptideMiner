# PeptideMiner: Learning the rules of peptide self-assembly through data mining with large language models

Zhenze Yang [1,2], Sarah K. Yorke [3], Tuomas P. J. Knowles [3,*], and Markus J. Buehler [1,4,5,*]

[1] Laboratory for Atomistic and Molecular Mechanics, Department of Civil and Environmental Engineering,
Massachusetts Institute of Technology, 77 Massachusetts Ave. Room 1-235A-B, Cambridge, 02139, MA, USA
[2] Department of Materials Science and Engineering, Massachusetts Institute of Technology, 77 Massachusetts Ave.,
Cambridge, 02139, MA, USA
[3] Yusuf Hamied Department of Chemistry, University of Cambridge, Lensfield Road, Cambridge, CB2 1EW, UK
[4] Center for Computational Engineering, Massachusetts Institute of Technology, 77 Massachusetts Ave., Cambridge,
02139, MA, USA
[5] Center for Materials Science and Engineering, Massachusetts Institute of Technology, 77 Massachusetts Ave.,
Cambridge, 02139, MA, USA

*mbuehler@mit.edu, tpjk2@cam.ac.uk

ABSTRACT: Peptides are ubiquitous and important biologically derived molecules, that have been found to self-assemble to form a wide array of structures. Extensive research has explored the impacts of both internal chemical composition and external environmenta stimuli on the self-assembly behaviour of these systems. However, there is yet to be a systematic study that gathers this rich literature data and collectively examines these experimental factors to provide a global picture of the fundamental rules that govern protein self-assembly behavior. In this work, we curate a peptide assembly database through a combination of manual processing by human experts and literature mining facilitated by a large language model. As a result, we collect more than 1,000 experimental data entries with information about peptide sequence, experimental conditions and corresponding self-assembly phases. Utilizing the collected data, ML models are trained and evaluated, demonstrating excellent accuracy (>80%) and efficiency in peptide assembly phase classification. Moreover, we fine-tune our GPT model for peptide literature mining with the developed dataset, which exhibits markedly superior performance in extracting information from academic publications relative to the pre-trained model. We find that this workflow can substantially improve efficiency when exploring potential self-assembling peptide candidates, through guiding experimental work, while also deepening our understanding of the mechanisms governing peptide self-assembly. In doing so, novel structures can be accessed for a range of applications including sensing, catalysis and biomaterials.
