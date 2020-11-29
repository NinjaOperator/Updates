Update 11/29/20

 So for the next installment of my GitHub repository “Indicators With Some Juice I’m collaborating with my ex-colleague Keagan Davis. 
 Where we will take a deep dive into the Turla report that Accenture released. 
 ( https://www.accenture.com/us-en/blogs/cyber-defense/turla-belugasturgeon-compromises-government-entity?src=SOMS&s=09). 
 And hopefully provide some additional context related to the indicators that Accenture provided in their report. 

Also in regards to my “Mustang-Panda Possible-Linked-To-Ransomware” report. As I stated in my analysis I found some overlap in a Rich PE Header hash from a recent binary that is tied to Mustang and a Encrp Ransomware payload. I hypothesized that it was likely that these two binaries were created by the same developer. However I was informed from a Threat Researcher (from a respectably Threat Intel vendor) that this overlap in infrastructure was due to using the same version of WinRAR which is why the imports and rich header is identical.
So therefore I find no reason to continue going down this rabbit hole since there isn’t any hard data indicating that Mustang Panda is utilizing ransomware in their campaigns.  
