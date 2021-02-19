# Creative-Project-1

## Summary of my Creative Project 1

In this Creative Priject Number 1 I decided to work with two short fantasy & Science Fiction novelettes by Ted Chiang  **Tower of Babylon & The Merchant and the Alchemist's Gate** they are both a part of the short stories collections **Exhalation: Stories**. 

* **The Merchant and the Alechemist's Gate**:_Tells the story of a merchant who meets a shop owner who invites Fuwaad into the back workshop to see a mysterious black stone arch which serves as a gateway into the future, which the shop owner has made by the use of alchemy. Fuwaad is intrigued, and the shop owner tells him three stories of others who have traveled through the gate to meet and have conversation with their future selves. When Fuwaad learns that the shop keeper has another gate in Cairo that will allow people to travel into the past, he makes the journey there to try to rectify a mistake he made twenty years earlier_ 

* **Tower of Babylon**: _Tells the story of Hillalum. A miner from Elam who has been summoned to the Tower of Babylon, an enormous brick tower that has been in continuous construction for centuries. He and his colleagues have been hired to dig through the Vault of Heaven to discover Yahweh's creation. Hillalum alone passes safely through the Vault. After a perilous journey ever-upwards, he finds that he has reemerged back at the surface, some distance from the Tower, rather than in Heaven as expected._

Since the two stories have a lot of  science fiction themes in common. I wanted to see what would be the restlt of those themes if **combined** To achieve the results I had to go throught two steps using *Markovify* & *GPT-2* 

**1.** first step was using **Markovify** I copied bothe short stories in one single TXT document. I curated the format of the text into one single block combining the two texts. Later I uploaded the text into ipynb file and run the code using Exercice 1 as a reference. 

**Here is a sample output from the combined texts using Markovify** 

_I confess I did not feel the lack.He was wandering by the dawn, until he was a workshop, arrayed with devices whose functions I could endure.Could his older self, now an aged woman.He bought extra hemp, and thus had material to work for Taahira's brother would not have sold it.Hillalum was again pulling on the verge of tears.He stood in the days of their task, finally, and after they had reached the ramp, and they were quite distinct.But it could not have killed Hassan.Hillalum and Nanni came over to them, **staring at the elbow, and he found it entertaining**, but did not speak to her husband's younger self, he left Cairo to identify himself as Ajib's_

I think that the results are quite intersting in a way since they have a sort of added a humoristic aspect to the story, which was lacking in the original text, since it reflects like more heavy topics such as divinity, time, etc.. Although other may argue thatstaring at the elow is serious stuff.  

**2.** I copied the results after using the Markovify method in a another TXT file, uploaded them to the ipynb file and started working on the GPT-2 section. At first I had issues to add code in the same ipynb file of markovify#1 So what I did was seperate them and then once I made sure that they work seperatly. i added them in a new ipnyb file and it worked. I refered to excerice 2 and  Zach Whalen tutorials using the **GPT-2** mothod to finetune the text. I have to say that it is a bit furstrating that this mothod is considerably taking way more time that the Markovify method (It took litterally the whole night of the model training  to generate the results, in which I had to constantly make sure that the computer doesnt go to sleep or for the battery to die) . But I guess that the results are more tuned and curated. 

**Here is a sample output from the GPT-2 method after finetuning the text ** 

_. _


**So to wrap up, these are the instructiosn on running the project:**

1. Open the ipynb file
2. Upload the TXT files available in this repository to the project
3. Run the cells in order
4. In case there is a problem in one or more of those cells try to copy that past it in a new document 
5. Wait for the model to stop training 
6. After you've trained the model or loaded a retrained model from checkpoint, you can now generate text. generate generates a single text from the loaded model.
using the next line of codd: 

      ```
      gpt2.generate(sess, run_name='run1')

      ```
7. I hope you enjoy the results!


## Artist Statement

This creative project was fun to work on. I have to admit that sometimes the frustarion from the errors that occur in the code makes the process a bit frustrating but I enjoy the results genearted . So I think that frustartion is worth it. Another reason why I loved working on this creative project was the choice of the texts. I very much enjoy reading stories written by Ted Chiang. I think he manages to challenge the readers perspective on notions of life, death, time and appreaciation. his stories are essentially science fiction novelelettes. They discuss great philosophical issues that hunted our thoughts. I wanted to see what would be the outcome of those ideas after introducing AI to it.  I have to say that I had no clue what the outcome would look like. Wich sparked my interest even more. I used the knowldge that I gathered from working on Exercises 1&2 to work on this creative project. After reading this Article [link to Article!](http://theconversation.com/artificial-intelligence-talks-and-talks-the-story-since-2001-a-space-odyssey-96252) I had the idea of combining the short stories **Tower of Babylon & The Merchant and the Alchemist's Gate** with the script **2001 Space Odyssey** by Stanely Kubrick. I feel like the two creative works have many themes in common and they are both under science fiction genre. I also did that and I have to say I love the results generated. The two works are intersting seperatly, so by combining and adding a randomization feature to them. It creates an interesting and compelling outcome. I published the results of that as well on this repository. You can also run the project using the same steps (from 1 to 7) mentionned above. **Let me share with you a sample output from the GPT-2 method after finetuning the text ** 









I am now wondering how would this generated work would like in the form of a movie! I think it would be AWESOME! And I guess that poses the question of whether the genius on these two works of Art should be credited to the writers, the combinations of the two works of Art, the programmer, or the AI or maybe all of these elements combined.




