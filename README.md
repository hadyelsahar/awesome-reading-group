# Awesome Reading Group :books::books:

This repo contains a template for organising reading groups. This reading group is organized as short 30 minute meetings multiple times a week. No one is expected prepare slides and/or read the paper in depth. This makes it agile and highly sustainable. 

<blockquote> Having daily frequent groups is very stimulating, and creates very different rhythm compared to weekly-biweekly reading group; it allows to cover much bigger volume of information, even if it is not covered in-depth.  If certain  papers are very relevant to your domain of interest you may go more in-depth by yourself or in smaller groups. </blockquote>

Please feel free to give any feedback on current organisation as a new issue to this repository - it can be adapted to our needs.   

## Kudos 
<img src="https://i.imgur.com/Zy0NvAf.png" height=150><img src="https://i.imgur.com/PStkLIK.png" height=150><img src="https://i.imgur.com/BozhFvv.png" height=150>

Kudos Lucy Park (Papago NAVER) for coming up with the idea of Agile Reading groups, and to Vassilina Nikoulina (NaverLabs Europe).

## Success stories 
- NaverLabs Europe NLP team (+80 papers / 5 Sprints first 7 months).
- Egyptian NLP community (10 papers first 3 months). 
  
## :watch: Time and Location 
#### Monday, Tuesday and Thursday xx-xxpm in [physical_location]
#### Remote participation:
https://zoom.us/j/xxxxxxxxxxxxxxxx

###### The time/frequency can be adjusted based on your feedback. The objective is to share and discuss interesting papers together on a regular basis.

## TLDR;
   - :heavy_plus_sign: :+1: [Add papers](https://github.com/hadyelsahar/awesome-reading-group/issues/1) and vote on papers you would like to read/discuss
   - :full_moon_with_face: :new_moon_with_face: Everybody is free to attend or not attend; 
   - :memo: Give the paper a read before as much in details, focus on specific parts  
   - :loudspeaker: At the beginning of the sessions a volunteer does a brief introduction of the paper
   - :speech_balloon: Attendance (usually groups 5-8 participants) can discuss, share impressions, ask questions 
   - :hourglass_flowing_sand: Try to keep it 30 minutes.   
   - :pencil2: take 5 mins to write your reflections on the discussion or add extra thoughts. 

## Detailed Intstructions

**1 - ADD and VOTE on papers as comments in the** [voting 
issue](https://oss.navercorp.com/nle-nlp/NLE-NLP-Reading-group/issues/1)
You may only put the title and the link to the paper, or add any comments to help people to understand why it is worth reading.

<kbd>
<img  src="https://i.imgur.com/jsidP0X.png" width=400px>
</kbd>


**2 - The top voted comment from "voting issue" gets selected**
The corresponding comment gets deleted from the voting issue and a new issue is created with the date of discussion:

<kbd>
<img src="https://i.imgur.com/QNAPoI3.png" width=600px>
</kbd>

**3- Read the selected paper according to one's time/knowledge​**
- The next papers to be discussed are added with the discussion date
- You don't have to read everything
- You are not supposed to understand everything
- The purpose of the multi-view discussions is to save time reading all papers in details as different participants will have focused on different parts of the paper. 

**4- Attend the reading group** 
- **several times a week*
- The main value of such reading groups is in the discussion; even if you didn't read the paper in depth - everybody pays attention on different things, which are shared during the discussion. Thus, it allows you to cover each paper more than if you would have read it by yourself.  

**4'- Sprints** 

 -Sometimes the reading group can go beyond a single paper: eg. conference proceedings, several papers around the same subject, etc.  The idea of the sprint is to grasp the as much papers as possible in a short time. We block 2h slot for this. The sprint happens in two phases:

 - during 45 min everybody goes through papers, selects the titles they are interested it, try to read through to get an idea of the paper, and give it a note on 1-10 scale for 'worth reading in details'. You may add a short comment about 'why it is interesting, worth reading, what it is about' or any reminder for yourself.
 - after 45 min of individual reading we sort the papers based on 'collective' score they got, and go through them one by one. People who have voted for the papers should 'convince' others that the papers is worth reading into more details.
This is a way to get a pretty broad coverage of the conference proceedings, even in the case when nobody attended the conference.

 - Examples of successful sprints are those made after conference acceptance notifications. 
 
<kbd>
<img src="https://i.imgur.com/DuK2sBM.png" width=300px>
</kbd>

**5- After discussion add your thoughts as a comment on the issue of the discussion day (NOT the voting issue)**
<kbd>
<img src="https://i.imgur.com/1v8miYh.png" width=300px>
</kbd>

**6-watch the repo so you get email updates with new meetings**

<kbd>
<img src="https://i.imgur.com/4ZPzzd5.png" width=200 style="border-style: solid;border-width: 1px;">
</kbd>


**7- Collect papers on a shared Zotero group**

<kbd>
<img src="https://www.zotero.org/support/lib/exe/fetch.php?tok=2735f1&media=https%3A%2F%2Fwww.zotero.org%2Fstatic%2Fimages%2Fpromote%2Fzotero-logo-128x31.png" height=20> 
</kbd>

All papers and comments get collected on zotero send an email to the Reading group admin If you would like to be invited to this zotero group

To extract comments from github issue to paste in a zotero group as comments paste this JS code to browser's console
```
var a = document.getElementsByClassName("d-block comment-body markdown-body  js-comment-body")
var alltext = "" 
for (i = 0; i < a.length; ++i) { 
	ps = a[i].getElementsByTagName("p")
	
	for (j=0; j<ps.length; j++){
		alltext += ps[j].textContent
    }
	alltext += "\n-----------\n"
}

console.log(alltext)
```

