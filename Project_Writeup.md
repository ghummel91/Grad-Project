---
title: MOLB 5845 Graduate Project
author: Gwen Hummel
date: December 9, 2019
---

Gwen Hummel
MOLB 5485: Computers in Biology Final Project
1. Assess read quality: 
PedCon1_R1 sequence: Utilizing the Per base sequence quality graphic in the FastQC Report, it is apparent that the majority of bases are of a high quality, with a small amount of sequence quality suffering toward the end of the read. This indicates that little trimming may be needed. Utilizing the Per sequence quality score graphic, we see that the average quality of our forward read remains high, with a PHRED score of roughly 36. The Per base sequence content graphics are where our FastQC summary first generated a red X. This is because there are many regions of the graphic where nucleotide content exceeds 25%, indicating that nucleotides have not been represented evenly throughout our sample. In this forward read, these discrepancies occur at the beginning and end of the read. The summary of the FastQC file also generated a red X at the Per sequence GC content graph, where we can see that the average GC content of this read was lower than the average theoretical distribution. The FastQC report also generated a red X failure notification at the Sequence Duplication Levels graph, indicating that over 50% of the sequence is non-unique. However, the report only generated 5 non-unique sequences.
   
PedCon1_R2 sequence: Following the Per base sequence quality graphic in the FastQC report, we see that the end of this reverse sequence is not of the same quality as the forward sequence. While the read quality remains at a high level, the final 1/4 of the sequence drops in quality compared to the forward read. This is to be expected of a reverse read. However, like our forward sequence, we can determine that the average quality of the read is high, based on the Per sequence quality scores graphic, with a PHRED score of roughly 36. Like the forward read, the Per base sequence content graphic was the first summary measure to be indicated as a failure with a red X. This is because several nucleotides are indicated to have a representation greater than 25%, both at the beginning and end of the read, indicating that there may be some sort of bias in the library preparation or the sequencing method. Unlike the forward read, the Per sequence GC content graphic of the reverse read is only indicated with a yellow warning in the summary. This is because the GC content is far more centered on the average distribution curve, even if it does not fit the normal distribution perfectly. The Sequence Duplication Levels graphic is similar to the forward read, and is also marked as a failure , indicating the over 50% of the sequence is non-unique. Unlike the forward read, the reverse read summary identified 18 overrepresented reads, possibly accounting for the lower quality of the reverse read.
  
 
2. There did not appear to be any undue noise at the front of the reads or obvious Illumina adapter contamination. The PHRED-scale was already high (36) for both reads and the FastQC website stated that a low PHRED score is anything <20. Based on information on the FastQC website, as well as the Babraham Bioinformatics website, I determined my best trimming option using Trimmomatic would be to use the sliding window command, to eliminate reads below average quality. The head crop command appeared unnecessary at this step. Instead of setting the sliding window to 24 like we did in class, I set it to 28, since this was the cutoff between good and average reads in the graphs depicted above. 
3. It took many attempts to iron out my coding for this section, the steps of which are detailed in both the project README file and history saved for session 2. 
While performing trimming, I first used the specifications outlined in class to be sure my code was identical to what the Trim.sh file needed. With the specifications HEADCROP:10, SLIDINGWINDOW:4:24, and MENLEN:80, the reverse paired read looked like this: 
  
 
I only got back the reverse read for this first run, but the trim mirroring the steps in class appeared effective. The PHRED score was the same, but the GC content was more consistent. However, as seen in the quality score, the trimming may have been a little excessive. I wanted to correct this with my original idea for trimming, which was to include just the SLIDINGWINDOW:4:28 command. I corrected this in the Trim.sh file. 
After running just the SLIDINGWINDOW command, my forward and reverse reads definitely had an improvement in quality, but the GC content seemed to suffer for my trim. The PHRED score did not change for either read. Here are the images for the forward read:
  
 
And the graphics for the reverse read: 
  

 
Because the HEADCROP function I included in my original test seemed to eliminate noise, where I previously hypothesized it would not, I included this command in my final trim. This trim now included HEADCROP:10, SLIDINGWINDOW:4:28.
Conclusion
I kept receiving an error in my SLURM email stating I was out of memory. I do not know if this is due to my training account or not, but was unable to add my HEADCROP changes back into the original Trim.sh file. However, I know that if I was able to complete this trim to my specifications, by both eliminating noise at the beginning of the read and improving the quality of what was included in the read, I would arrive at decent RNA sequence for further processing and research.. 
