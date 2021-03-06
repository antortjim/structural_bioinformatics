# Structural Bioinformatics

Code and data generated in the final hand in for the course Structural Bioinformatics at the MSc in Bioinformatics from University of Copenhagen.
PDF at http://people.binf.ku.dk/rnq313/rmsd_nmers/protein.pdf

The hand in consisted of separated RNA and Protein parts. The code is organized accordingly.

### Getting the code

Please run this in your command line

``git clone https://github.com/antortjim/structural_bioinformatics.git``


## Protein part

To run the code in the protein part:

Leave your dataset of pdb files into a folder called **top**.

The folder containing the cloned repo should be in the same folder as top:  


├── **structural_bioinformatics**  
│   ├── database  
│   ├── protein  
│   ├── README.md  
│   ├── rna  
│   └── shiny  
└── **top**  
    ├── *PDB File 1*  
    ├── *PDB File 2*  
    ├── ...  
    


**Run**

``FLEN=5 # set to the desired n-mer (fragment) length``

``cd structural_bioinformatics/protein``

``python protein.py $FLEN``

Output is generated in shiny/out
