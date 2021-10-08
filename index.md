# __<span style="color:#D57500">MS-GF+</span>__
MS-GF+ (aka MSGF+ or MSGFPlus) performs peptide identification by scoring MS/MS spectra against peptides derived from a protein sequence database. It supports the HUPO PSI standard input file (mzML) and saves results in the mzIdentML format, though results can easily be transformed to TSV. ProteomeXchange supports Complete data submissions using MS-GF+ search results.

### Description
MS-GF+ identifies peptides in LC-MS/MS datasets.  It is optimized for a variety of spectral types, i.e., combinations of fragmentation method, instrument, enzyme, and experimental protocols. It supports a variety of input file formats, including mzML, mzXML, Mascot Generic File (mgf), MS2 files, Micromass Peak List files (pkl), and Concatenated DTA files (_dta.txt)

### Publications
[MS-GF+: Universal Database Search Tool for Mass Spectrometry, Sangtae Kim, Pavel A. Pevzner, Nat Commun. 2014 Oct 31;5:5277. doi: 10.1038/ncomms6277.](https://pubmed.ncbi.nlm.nih.gov/25358478/)

[Spectral Probabilities and Generating Functions of Tandem Mass Spectra: A Strike against Decoy Databases, Sangtae Kim, Nitin Gupta and Pavel Pevzner, J Proteome Res. 2008 Aug;7(8):3354-63. doi: 10.1021/pr8001244.](https://pubmed.ncbi.nlm.nih.gov/18597511/)

### Downloads
* [Latest version](https://github.com/MSGFPlus/msgfplus/releases/latest); zip file contains:

  | File | Description | Requirements |
  |---|---|---|
  | MSGFPlus.jar | MS-GF+ search engine | Java Runtime |
  | MzidToTsvConverter.exe | Converts .mzid files to a tab-delimited text file | .NET Runtime 4.6.2 or newer
  | Documentation files | HTML files explaining how to use the software | n/a
  | Example files | Example modification files and example results | n/a
* [Source code on GitHub](https://github.com/MSGFPlus/msgfplus)

### Documentation
Pages describing the use of MS-GF+, the Mzid to TSV Converter, and the Suffix Array Builder (BuildSA) are hosted on GitHub, see the [MS-GF+ Documentation](https://msgfplus.github.io/msgfplus/)

### License
This software is Copyright © 2012, 2013 The Regents of the University of California. All Rights Reserved.

Permission to copy, modify, and distribute this software and its documentation for educational, research and non-profit purposes, without fee, and without a written agreement is hereby granted, provided that the above copyright notice, this paragraph and the following three paragraphs appear in all copies.

Permission to make commercial use of this software may be obtained by contacting:
Technology Transfer Office
9500 Gilman Drive, Mail Code 0910
University of California
La Jolla, CA 92093-0910
(858) 534-5815
invent@ucsd.edu

This software program and documentation are copyrighted by The Regents of the University of California. The software program and documentation are supplied "as is", without any accompanying services from The Regents. The Regents does not warrant that the operation of the program will be uninterrupted or error-free. The end-user understands that the program was developed for research purposes and is advised not to rely exclusively on the program for any reason.

IN NO EVENT SHALL THE UNIVERSITY OF CALIFORNIA BE LIABLE TO
ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING
OUT OF THE USE OF THIS SOFTWARE AND ITS DOCUMENTATION,
EVEN IF THE UNIVERSITY OF CALIFORNIA HAS BEEN ADVISED OF
THE POSSIBILITY OF SUCH DAMAGE. THE UNIVERSITY OF
CALIFORNIA SPECIFICALLY DISCLAIMS ANY WARRANTIES,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.
THE SOFTWARE PROVIDED HEREUNDER IS ON AN "AS IS" BASIS, AND THE UNIVERSITY OF CALIFORNIA HAS NO OBLIGATIONS TO
PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR
MODIFICATIONS.
