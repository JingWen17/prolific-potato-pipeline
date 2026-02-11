# A detailed notes about using Prolific

## Key Steps

### 01 <span style="color:red;">Start a new project</span>

Once you've entered the Prolific with your account, you'll find the *Projects* option on the left, as the following picture.<br> 
This page list all projects you have for now, including completed, ungoinng and draft ones.<br> 
<img width="50%" alt="image" src="https://github.com/user-attachments/assets/82bb1fff-b2f8-4cfd-a5ed-9d9d588819b6" />


Then by clicking on *New project*, you will create a new project as either a single study or a folder that can collect more studies as a collection.<br>
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/6c81f9ec-a450-4aaa-89ff-b4a3d4945749" />

### 02 <span style="color:red;">Start a new study</span>

In the project, you can create a new study by clicking on *New study*.   
<img width="40%" alt="image" src="https://github.com/user-attachments/assets/c6f4d73b-764e-4ed7-ae93-7f98e8344b53" />

This will take you to a study setting up page that allows you to customize your studies across five sections:  

1. <u>Data collection type</u>
   
   <img width="30%" alt="image" src="https://github.com/user-attachments/assets/abb8d3c2-b7e4-4000-bc87-7fb46e9eb6b7" />
   
   There are four options for your study's data collection type, and in our case to use Potato, we need to provide our own study URL (*External study link*).

2. <u>Study details</u>
   
   <img width="30%" alt="image" src="https://github.com/user-attachments/assets/68483653-e062-46c8-bb1b-7bb6f12eb517" />
   
   <span style="color:blue;">*Study name*</span> - is the name visible to participants
   
   <span style="color:blue;">*Internal study name*</span> - is the optional additional name for yourself
   
   <span style="color:blue;">*Data collection type*</span> - is the type of your study, like survey or writing tasks, that need to be done by the partipants
   
   <span style="color:blue;">*Device requirements*</span> - allows you to control that your studies can only accessible for users who use the laptop (to make sure they see a stable webpage layout), and require them to provide additional sources other than texts
   
   <span style="color:blue;">*Lables*</span> - enables participants to be warned by sensitive or disturbing content before entering your study

   
3. <u>Data collection</u>

   <img width="30%" alt="image" src="https://github.com/user-attachments/assets/81f2ed3d-6e4c-4562-8345-1b9dc5437512" />

   <span style="color:blue;">*What's the URL of your study?*</span> - needs to be filled in with the url you use to host your survey webpage with Potato, more details can be found in potato.md and pipeline.md files

   <span style="color:blue;">*Recording Prolific IDs*</span> - by cliking on *URL parameters*, it requires participants only who has a Prolific ID can enter your study, and participants will only show the anonomous ids

   <span style="color:blue;">*Custom screening*</span> - allows an automatic check on participant match, and adding it costs more

   <span style="color:blue;">*Completion paths*:</span>

       <span style="color:blue;">*Manually review*</span> - requires you manually approve EACH participant's results once they have finished so that they can get paid
   
       <span style="color:blue;">*Approve and pay*</span> - will automatically approve ANY partcipant's results and pay to them. However, if participants spend too little time on your study than the average time, or finish your study without a valid completion code, these answers will wait for your manual approval
   
    <span style="color:blue;">*Redirect URL & Copy and paste code*</span> - when you create a new project, a completion code will be automatically generated. This code allows participants' results to be viewed as completed or valid. The *Redirect URL* will need to be set in Potato, which can be found in potato.md. Always make sure that the code and the redirect URL showed here on Prolific, and this set in the Potato is the same.
   

   
4. <u>Recruit participants</u>

   <img width="30%" alt="image" src="https://github.com/user-attachments/assets/6ebc30d6-b57a-4c61-a2dd-29c9b0665d78" />

   <span style="color:blue;">*Source*</span> - allows you to either indicate new rules for recruiwting participants or use a saved one

   <span style="color:blue;">*Participants*</span> - the total number of participants recriuwted in this study. Numbers that is below three might make more time maybe because people are less interested in fewer-positioned studies or some other reason

   <span style="color:blue;">*Screening*</span> - allows you to filtering participants according to your requirements, such as gender, countries or education level

   <span style="color:blue;">*Study distribution*</span> - defines how your participants are distributed

   <span style="color:blue;">*Credentials*</span> - if you want specific logins

   <span style="color:blue;">*Submissions*</span> - defines if the same participant can take part in this study only once or more than once

   <span style="color:blue;">*Reject exceptionally fast submissions*</span>  - defines if you want the super-fast submissions to be automatically rejected
   
5. <u>Cost</u>

   <img width="30%" alt="image" src="https://github.com/user-attachments/assets/0690cf94-fb21-4ac6-a8f9-b4a35d062943" />

   <span style="color:blue;">*How long will your study take to complete?*</span> - is your estimated time for one participant complete this study. It will be used for automatically measuring the total cost of this study.

   <span style="color:blue;">*How much do you want to pay?*</span> - is the payment for each participant

   <span style="color:blue;">Important</span>:
   
   The total cost of this study is calculated by $NumberOfParticipants \times EachParticipant'sPayment$. The hourly price is calculated by $EachParticipant'sPayment \div EstimatedCompletionTime \times 60$. This hourly price must be higher than 6 according to Prolific requirements. In addition, if EstimatedCompletionTime is much lower than the actual average one, and if the payment for each participant you've defined is too low, then the eventual hourly price may be lower than 6 after your study is finished. In that case, you need to make a compensation to your participants so that the hourly price is at least 6. Refusing to do so may put yourself being restricted by Prolific for future studies. (I haven't compared the prices between setting up a correct price beforehand and setting up a least valid hourly price plus compensation leater on. So not much information about which one costs more. Participants' completion times can vary from person to person, and even same study may end with different average time if run twice. However, it's always good to run a test study within your friends or colleges, or with a small group of participants to get some information about the estimated submission time.) 


### 03 <span style="color:red;">Before publish your study</span>

You can preview your study as a participant by clicking on *Preview as participant*.

Make sure your survey is running defined by Potato before publishing your study on Prolific.

Make sure you have enough money in your account.

### 03 <span style="color:red;">Publish</span>

Once your study is published, it will take some time for the first participant entering your study. And you can see the details of how many participants entering or completing your study on the prolific.

In addition, prolific enables the communication between study publishers and participants through chatting rooms on Prolific shown as *Messages*. Keep an eye onm these messages after you publish your study. It allows you to quickly get information about systematic errors from participants if they encounter any problems so that you can stop your study and fix them without losing too much money.




## Related Notes
- Link to other files

