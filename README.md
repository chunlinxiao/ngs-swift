# NGS-SWIFT

<b>Introduction</b>

<sub>NGS-SWIFT is a customized computational environments and software packages essential for DNA and RNA sequence analysis with public and control-accessed NGS data in cloud. Instantiation of an cloud instance or instance clusters with ideal computing environment is much facilitated.</sub>

<sub><b>Included tools are: </b><br />
  Popular aligners (bwa, bowtie2, soap2 etc), <br />
  Variant callers (samtools/bcftools, freebayes, snptools, soapsnp, cortex, varscan etc), <br />
  RNAseq analysis tools (tophat, cufflinks, STAR, hisat etc), <br />
  Common utility tools (vcftools, bedtools, tabix, R etc), <br />
  NCBI developed SRA Toolkit and NGS Software Development Kit, and<br />
  *Assembly tools (falcon, soapdenovo, sga, wga/CA etc) </sub><br />


<br />
************************************************************************************************

<b>Full Features</b>

* <sub>Customized AMI with pre-configured tools - no more installations and configurations for tools</sub>
* <sub>Analyzing control-accessed dbGaP data directly without downloading - saving disc spaces and downloadin time</sub>
* <sub>Flexibility  - users can add their own (proprietary or licensed) tools as they like </sub>
* <sub>*Accessing public s3 NGS data like local file system - saving disc spaces and data transferring time</sub>


<br />
************************************************************************************************

<b>Latest release and suitable platform</b>

<sub><b>ngs-swift-20150621-ubuntu14.04-x86_64-light </b> in Amazon aws cloud  (Features with * excluded from light version AMI. If you need ngs-swift AMI with full features, please send your request to xiao2@mail.nih.gov). </b></sub>

<br />
************************************************************************************************

<b>Testing</b>

<sub>For testing with control-accessed data, user can follow the instruction described in this document: [AWS_control_accessed_1KG_data_Instructions_v1.3.docx](https://github.com/chunlinxiao/ngs-swift/blob/master/docs/AWS_control_accessed_1KG_data_Instructions_v1.3.docx).

<br />
************************************************************************************************

<b>Contact</b>

<sub>If you have any suggestion ro question regarding ngs-swift, please consult with Chunlin Xiao at xiao2@mail.nih.gov</sub>.


<br />
************************************************************************************************

<b>Disclaimer</b>

<sub>Please be aware that it is the user's responsibility to comply all the related policies and 
regulations regarding the use of Cloud Computing Services for Storage and Analysis of 
Controlled-Access Data Subject to the NIH GDS Policy. The services, software and analysis 
procedures included in this image are just provided for convenience and demonstration ONLY, 
and DO NOT imply any endorsement or justification by the NIH and the United States Government. 
It is also the user's responsibility to ensure the compliance with the licensing requirements 
of the software being used.</sub>
