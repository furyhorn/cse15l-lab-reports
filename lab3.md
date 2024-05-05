Part 1


Part 2
4 interesting command-line options for `grep`
1. `grep -i`
Citation: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
```
grep -i "cloud" biomed/*.txt
biomed/1471-2156-2-18.txt:          segment cloudiness often made ophthalmoscopy difficult in
biomed/1471-2164-3-18.txt:        interpretation of these proteomic data is clouded by the
biomed/1471-2180-3-11.txt:        highly polymorphic clouds of mutants, so-called
biomed/1471-2202-3-5.txt:          center of the cloud of points defined by the respective
biomed/1471-2288-2-4.txt:        TPR for each region would lead to a cloud of points, rather
biomed/ar612.txt:        further clouded by the apparent contradictory findings that
biomed/gb-2002-3-12-research0072.txt:          fall in the cloud of background scores under all three
biomed/gb-2002-3-3-research0011.txt:          'cloud' of genes is plotted on a scatterplot. This view
biomed/gb-2002-3-3-research0011.txt:          because overlaying clouds of thousands of gene vectors
biomed/gb-2002-3-4-research0018.txt:          independently. In ideal terms, the scatter cloud is
biomed/gb-2003-4-9-r57.txt:          native genes cloud. These last genes may therefore
biomed/gb-2003-4-9-r57.txt:          however, localized in the cloud of points of the
```
Explanation:
This command searches for occurrences of the word "cloud" in all `.txt` files within the biomed directory, 
ignoring case distinctions. It's useful for quickly identifying mentions of "cloud" across multiple text files.

```
grep -i "snow" biomed/*.txt
biomed/1471-2148-2-15.txt:        "chicken" (also called the "snowdrift" or "hawk-dove"
biomed/1472-6785-1-5.txt:        winter weather, particularly snow conditions, on wolf-prey
biomed/1472-6785-1-5.txt:        population dynamics. Evidence of influences of snow on wolf
biomed/1472-6785-1-5.txt:        which are affected by many species other than snowshoe hare
biomed/1472-6947-2-7.txt:            Senators Graham and Snowe, has been introduced also in
biomed/bcr631.txt:          of tubulin was presented in detail by Lacey and Snowdon [
```
Explanation:
This command searches for occurrences of the word "snow" in all `.txt` files within the biomed directory, 
ignoring case distinctions. It's useful for quickly identifying mentions of "snow" across multiple text files.



2. `grep -v`
Citation: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
```
grep -v "authors" plos/pmed.0020191.txt        
The excellent article by Jordan Paradise, Lori B. Andrews, and colleagues, “Ethics.
Constructing Ethical Guidelines for Biohistory” [1], neither advocates nor argues against
biohistorical research; instead, it points out that such investigations are currently
taking place without guidelines—ethical, scientific, moral, or religious. The question
remains: if such guidelines were to be established, what individuals, institutions,
governments, medical examiners, family members, or intrepid biographers are to be given
permission? Who is to decide what is “historically significant”? Not to mention the
comments [2] implied that they took a position on this issue.
```
Explanation:
This command searches for lines in the `plos/pmed.0020191.txt` file that do not contain the word "authors". 
It's useful for filtering out lines that mention "authors" from the text file.

```
grep -v "article" plos/pmed.0020191.txt
Constructing Ethical Guidelines for Biohistory” [1], neither advocates nor argues against
biohistorical research; instead, it points out that such investigations are currently
taking place without guidelines—ethical, scientific, moral, or religious. The question
remains: if such guidelines were to be established, what individuals, institutions,
governments, medical examiners, family members, or intrepid biographers are to be given
permission? Who is to decide what is “historically significant”? Not to mention the
meta-question: who is to decide who is to decide? I apologize to the authors if my brief
comments [2] implied that they took a position on this issue.
```
Explanation:
This command searches for lines in the `plos/pmed.0020191.txt` file that do not contain the word "article". 
It's useful for filtering out lines that mention "article" from the text file, 

3. `grep -c`
Citation: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
```
grep -c "911" 911report/*.txt
911report/chapter-1.txt:0
911report/chapter-10.txt:0
911report/chapter-11.txt:0
911report/chapter-12.txt:0
911report/chapter-13.1.txt:0
911report/chapter-13.2.txt:0
911report/chapter-13.3.txt:0
911report/chapter-13.4.txt:0
911report/chapter-13.5.txt:30
911report/chapter-2.txt:0
911report/chapter-3.txt:0
911report/chapter-5.txt:0
911report/chapter-6.txt:0
911report/chapter-7.txt:0
911report/chapter-8.txt:0
911report/chapter-9.txt:40
911report/preface.txt:0
```
Explanation:
This command counts the occurrences of the number "911" in each `.txt` file within the 911report directory. 
It's useful for quickly understanding the distribution of references to "911" across different chapters or sections of the 9/11 Commission Report.

```
grep -c "author" 911report/*.txt
911report/chapter-1.txt:16
911report/chapter-10.txt:2
911report/chapter-11.txt:10
911report/chapter-12.txt:16
911report/chapter-13.1.txt:34
911report/chapter-13.2.txt:11
911report/chapter-13.3.txt:18
911report/chapter-13.4.txt:33
911report/chapter-13.5.txt:20
911report/chapter-2.txt:5
911report/chapter-3.txt:61
911report/chapter-5.txt:9
911report/chapter-6.txt:24
911report/chapter-7.txt:7
911report/chapter-8.txt:5
911report/chapter-9.txt:4
911report/preface.txt:0
```
Explanation:
This command counts the occurrences of the word "author" in each `.txt` file within the 911report directory. 
It's useful for quickly obtaining a summary of how many times the term "author" appears in each chapter or section of the 9/11 Commission Report.

4. `grep -h`
Citation: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
```
grep -h "call" 911report/chapter-12.txt
Because the Muslim world has fallen behind the West politically, economically, and
    hundreds of lives, can be mounted locally. Their requirements are far more modest in
        the pit we find ourselves in, to raise ourselves up," Musharraf has called for a
    the state grew dramatically. Substantial sums went to finance Islamic charities of
    In June 2004, the Saudi ambassador to the United States called publicly-in the Saudi
    called for greater economic and political reform.
Practically every aspect of U.S.counterterrorism strategy relies on international
    dramatically, and often in an ad hoc way, that it is difficult to track these
        Conventions on the law of armed conflict. That article was specifically designed
    Qaeda-perhaps drastically-but it is too soon to know if this reduction will last.
Before 9/11, no agency of the U.S. government systematically analyzed terrorists'
    the terrorist predecessors to al Qaeda had been systematically but detectably
    laws-that is, aspects of those laws not specifically aimed at protecting against
    liberties. These problems should be addressed systemically, not in an ad hoc,
    called algorithms, are just beginning to be used. Travel history, however, is still
    recorded in passports with entry-exit stamps called cachets, which al Qaeda has
        governments could dramatically strengthen America and the world's collective
    screening program, called US VISIT (the United States Visitor and Immigrant Status
    current efforts do not yet reflect a forward-looking strategic plan systematically
    called CAPPS. More than half were identified for further inspection, which applied
Many of our recommendations call for the government to increase its presence in our
    terrorists have used our open society against us. In wartime, government calls for
This shift of power and authority to the government calls for an enhanced system of
```
Explanation: 
This command searches for lines containing the term "call" in the `911report/chapter-12.txt` file. 
It's useful for identifying instances where the term "call" is used within this chapter of the 9/11 Commission Report.

```
grep -h "911" 911report/chapter-13.5.txt
    received by civilians in the towers based on (1) calls to NYPD 911 from or
    September 11, 2001 (hereafter "Commission analysis of 911/PAPD calls"). Everyone
    Commission analysis of 911/PAPD calls; Civilian interview 17 (May 11, 2004);
    analysis of 911/PAPD calls; Port Authority transcripts of recorded Port Authority
32. Commission analysis of 911/PAPD calls.
    2004); Civilian interview 14 (Apr. 7, 2004); Commission analysis of 911/PAPD calls.
    7 (Mar. 22, 2004); Commission analysis of 911/PAPD calls. For some emergency
36. For callers being disconnected, see Commission analysis of 911/PAPD calls. For
    and terminations, see Commission analysis of 911/PAPD calls.
    callers, see Commission analysis of 911/PAPD calls. For standard operating
    911/PAPD calls. For operators departing from protocol, see ibid.
40. Commission analysis of 911/PAPD calls; Port Authority transcripts of recorded
43. For smoke rising and its effect, see Commission analysis of 911/PAPD calls. For
    911/PAPD calls; Port Authority transcripts of recorded Port Authority calls and
67. Commission analysis of 911/PAPD calls; NYPD recordings, City Wide 1, Special
    interview 4 (Mar. 16, 2004); Commission analysis of 911/PAPD calls. For events in
    (Mar. 16, 2004); Civilian interview 3 (May 4, 2004); Commission analysis of 911/PAPD
87. For conditions in the 90s and 100s, see Commission analysis of 911/PAPD calls.
    floors, see Commission analysis of 911/PAPD calls.
88. For the callers, see Commission analysis of 911/PAPD calls. There are many
    from floors higher up as well. It is not known, however, whether 911 callers had a
89. Commission analysis of 911/PAPD calls.
    2004); Commission analysis of 911/PAPD calls.
91. Commission analysis of 911/PAPD calls.
    Commission analysis of 911/PAPD calls.
96. Commission analysis of 911/PAPD calls. It is not clear whether callers from below
    simply calling to seek advice. In any case, the 911 operators and FDNY dispatchers
150. For the 911 call, see Commission analysis of 911/PAPD calls. For the inaccurate
157. For information about 911 calls, see Commission analysis of 911/PAPD calls. For
    www.whitehouse.gov/news/releases/2001/09/20010911-16.html).
```
Explanation:
This command searches for lines containing the term "911" in the `911report/chapter-13.5.txt` file. 
It's useful for isolating specific mentions or references to "911" within this chapter of the 9/11 Commission Report.
