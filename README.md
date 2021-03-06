# Central Knowledge Base

I have been thinking about creating a personal knowledge management system for a long time. I have used various software like Remnote, Notion, Obsidian, TiddlyWiki etc. Currently, I am using Notion to bookmark the websites I am going to read later and Remnote to organize my knowledge. While Notion is awesome piece of software to collect and organize files, it feels too much flexible for me. 

Remnote is perfect for study app, it has lot of features but one drawback at least for me: no way to write down something without bullet point and based on the model it follows, it's actually not feasible.

I want someting simpler which should be plain text file so that, even if I decide to move away from the software, I can keep all the files on my own. 

After a long time, I've come to a conclusion, I will try **Obsidian** for the next 3 months to build my personal knowledge management system.

I will use Obsidian with git functionaliy or Google Drive/Dropbox functionality, which I haven't decided yet.

A drwaback however using Obsidian is that I can' termux make work in my androind phone, which means I have no easy way to read my notes from my mobile without using Obsidian Sync
option which is not an option for me, at least right now.


## Update 01

I will start using Obsidian as my personal knowledge management system from **22-02-2022** and will be continued till **30-05-2022**

## Structure

For each topic, there will be a separate README file and each topic will have a _parent section_. 

- base (root)
    - section_name
        - <topic_name1.md>
        - <topic_name2.md>
        - ...

<del>Initially, I will use [onsidian-git](https://github.com/denolehov/obsidian-git) to sync between devices.</del>

It seems that I am facing git related error while using the above plugin in Windows environment. While it may take while to inspect the issue, I will use Obsidian with git for now. And to make things more long lasting, I will put the _vault_ folder at a cloud drive (google drive/dropbox/pcloud) in addition to **Cryptomator**. To sum up:

- **Obsidian**: as my central knowledge base as _second brain_
- **Git**: for version control
- **Github**: for hosting repository
- **Google** Drive/Dropbox/pCloud for secondary cloud backup
- **Cryptomator** to encrypt the content in cloud (although I still need to figure out how to work with this with minimal effort)

## Update 02


As I am initially planning to store information for learning purpose for now I won't need to use **Cryptomator**
