# L'espion

### Category
Threat Intelligence

### Tags
OSINT, GitHub, Bloodhound

### Walkthrough

Before we start, please download the challenge file. Upon unzipping, we found 3 files:
- Github.txt
- Office.jpg
- Webcam.png

With all preparation done, let's answer the questions!  

**Q1. File -> Github.txt:**   
**What is the API key the insider added to his GitHub repositories?**  

> aJFRaLHjMXvYZgLPwiJkroYLGRkNBW

Opening the zip, we found 3 files github.txt, office.jpg, and Webcam.png. In the Question Earlier it told us to open the GitHub.txt, inside the file, we can see a Github link https://github.com/EMarseille99. Q1 wants us to explore the Repositories, so I did and I found **"Login Page.js"** on the first Repository, and so we got our answer for Q1.


**Q2. File -> Github.txt**<br />
**What is the plaintext password the insider added to his GitHub repositories?**<br />
> PicassoBaguette99  
Still on the same file, we just need to scroll down a bit to see a encoded password. We can simply decode it with [CyberChef](https://gchq.github.io/CyberChef/).


**Q3. File -> Github.txt**  
**What cryptocurrency mining tool did the insider use?**  
> xmrig  

**Q4. What university did the insider go to?**  
> Sorbonee  

**Q5. What gaming website the insider had an account on?**
> Steam  

**Q6. What is the link to the insider Instagram profile?**  
> https://www.instagram.com/emarseille99/  

**Q7. Where did the insider go on the holiday? (Country only)**  
> Singapore  

**Q8. Where is the insider's family live? (City only)**  
> Dubai  

**Q9. File -> office.jpg**  
**You have been provided with a picture of the building in which the company has an office. Which city is the company located in?**  
> Birmingham  

**Q10. File -> Webcam.png**  
**With the intel, you have provided, our ground surveillance unit is now overlooking the person of interest's suspected address. They saw them leaving their apartment and followed them to the airport. Their plane took off and has landed in another country. Our intelligence team spotted the target with this IP camera. Which state is this camera in?**  
> Indiana  