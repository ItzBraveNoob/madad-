# Sevaarth-Donation-Android-Mobile-Application

## Problem Statement
<p align = "justify">
To build a platform that will bridge the gap between donors and organizations. Application will serve the purpose for donating daily-need items like Food, Clothes, Books, etc and other crucial items like Blood, Medicines
as well. So, the main purpose is to connect trusted users without any intermediary service. With the advancement in technology, the internet-based mobile application will act as a bridge between the donors and the donation recipients. The people who are willing to donate (Food, Clothes,
Money, Medicines, Blood, etc.) can register through the application. The charity organization can also register and put up their requests for the required items.<br/>
<b> The main idea lies that the user can find the nearest needy organisation by choosing the category of items they want to donate. This will help the organisations to receive the donation items which they need. </b> <br/>
</p>

### Overview: <br/>
<p align = "justify">
1. The users can create an account based on their role, i.e., Donation Recipients and Donors. There will be no role of any third party here. The users have to register themselves by entering the basic details. <br/>
2. For The Donors, there will be an option to donate and categories to select the type of donation, i.e., food, clothes, books, etc, and also an option to select the preferred location of the organization.<br/>
3. After selecting the category, they will have a list of the organizations that need those things among them from which they can select whom they wish to donate. <br/>
4. They have to enter some details like their name, the details of items i.e. food, clothes, books, money, medicines, blood (in a pint) , and also an option to upload the image of the item. Donation reports will be sent to respected organizations via email.<br/>
5. On the Receiver's side, i.e.Organisation, there will be an option to check the donator’s details, location, and quantity based on category and enter the particular requirement from the categories which they need. Verification of organisations will be done by admins. <br/> 
</p>

### Stakeholders
1. <b> Donor </b> - A user which can donate any item to any organization to help the needy people.
2. <b> Organisation  </b> - This is a charity organization which takes the donations from the donors and make the distribution between the needy people.

## ScreenShots

### Session Onboarding:
<p align = "justify"> Using material design Onboarding i.e Application Walkthrough - An initial
hierarchy that creates meaning for our Application. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154636037-bbd503f1-ab50-495f-8163-21454ec35538.png" width=30% height=10%>    <img src="https://user-images.githubusercontent.com/43794593/154636053-c1dc8b4c-d99f-4e0c-a99b-a44f63f6889a.png" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154636058-d0b5f272-f418-4e96-b184-52d71098d170.png" width=30% height=30%> <br/>

### Registration and Login
<p align = "justify"> Provides the Login functionality for Already-registered users and New user registration for newbies. All the registered details will be saved in the created firebase Database. We have implemented a Role-based Login Feature, Where Donators or Organization will be redirected to their respective pages. We have used Email authentication service fr firebase console. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154636317-893fb5d9-d9d6-4f6e-b743-cc7679e470ab.jpg" width=30% height=30%>       <img src="https://user-images.githubusercontent.com/43794593/154636335-e02813ac-2b3e-4b63-bb6f-14d41fe0c79b.jpg" width=30% height=30%> <br/>

### Forgot Password
<p align = "justify">  If a user forgets his/her password there’s an option to reset the password which will be done over the mail. This functionality is provided over the Login Activity. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154636323-1a1b6130-d631-44fa-8f7d-a84d0c875af2.jpg" width=30% height=30%>   <br/>

### Donor
#### Dashboard for Choosing Donation Item and Location
<p align = "justify"> When a donor-user login to the application, then this activity will be displayed. In this dashboard activity, the donor can get the organization details by using the filter against the type of donation item i.e. Food, Books, Clothes, Blood, Medicines, Money and the location of the organization. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154641860-9dbb0727-f547-48b7-9f76-6c4c101bf7cc.jpg" width=30% height=10%>    <img src="https://user-images.githubusercontent.com/43794593/154641888-e09fccf2-a356-4b3b-b8ea-af2130ad85f6.jpg" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154641894-dcda3b76-212d-4f14-92ff-18d3e362bca6.jpg" width=30% height=30%> <br/>

#### Display Organizations
<p align = "justify"> Displays the list of Organizations on the recycler view. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154641931-f7a3d097-e933-4ec7-9970-727773dd4c68.jpg" width=30% height=30%>
<br/>

#### Display Details of Organizations 
<p align = "justify"> When we click any Organization in recycler view, The new activity will open where the user can see all the related details of respective organizations.  <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154641986-3ab85063-9ee6-436c-ba77-16bcf3754c6b.jpg" width=30% height=10%>    <img src="https://user-images.githubusercontent.com/43794593/154641990-db38234e-2f44-484b-91f1-cc0dd1f4b887.jpg" width=30% height=30%> <br/>

##### Locate, Chat and Call with Organization
<p align = "justify">  The user can see the location of the particular organization in google map by clicking on the top of the Location button. We can chat on whatsapp with that organization using the Chat Button that can be seen in the below of that organization details activity. We can call also that organization using the Call Button that can be seen below of that organization details activity. This Call option is providing us Phone Call, Skype Call, or Zoom Call for communication.  <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154642264-3ac83be6-ef2c-4d0f-869f-71724097021e.png" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154642273-fbe6c96f-9d6a-48fb-948b-57df08a886bb.png" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154642212-0214f851-9b0a-4f84-902c-572126163c83.png" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154642003-4842e9d3-a4ad-4d63-980c-b80923993073.jpg" width=30% height=30%> <br/>

##### Donation Form and Details
<p align = "justify">  If a donor wants to donate an item to a particular organization, then he/she will have to click on the Donate button that is seen in the above image. After that, the activity will populate for donation details which you want to donate.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154642982-1abc1e5f-917a-4dfb-97ef-c07e7f0202c4.jpg" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154642991-51b09633-4ba2-4b10-9c9d-0bc9a5053275.jpg" width=30% height=30%> <br/>

##### Sending Email
<p align = "justify">  Users can send the donation details to the organization via Email.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154643007-3534e100-7109-4af0-a927-6eafb45a1a58.jpg" width=30% height=30%><br/>

#### Event Creation, Hosting, Showcasing and Event Card Generation
<p align = "justify">  Donors can also host events that will get displayed on the dashboard. We can generate the pdf of events that is the event card which users can further refer for sending over email/ whatsapp.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154643189-815424dd-80dc-45a8-af16-295aaf1bca93.jpg" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154643193-6c6c89ec-bb58-4745-878d-ce7b808edeff.jpg" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154643204-c76d5d2b-bb82-44a6-9d1e-6e2f5df68a0a.jpg" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154643209-765fd42e-326f-4c27-8314-718c909bc9ef.jpg" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154643217-b21df805-225f-413e-9860-8b4c78bf5111.jpg" width=30% height=30%> <br/>

### Organisation
<img src="https://user-images.githubusercontent.com/43794593/154636730-6064c468-4603-4ee3-8d51-886cf84af896.jpg" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154636859-b117279b-ab71-4892-921a-05eebae220e5.jpg" width=30% height=30%>    
<br/>

#### View Profile
<p align = "justify">  Users can check his/her details like Name, Email, Password, Change Password, Upload Documents, Details verified or not, Docs uploaded or not.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154637372-3e56fdc4-dd1a-44b3-afcf-a19c33f39852.jpg" width=30% height=30%>     
<br/>

##### Update Profile
<p align = "justify">  Users can update all the details like Head of the Ngo, Area, Strength, Address, Requirements, Checkboxes of the Requirements, Phone Number, Descriptions and Images of their Organisation.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154637377-340670dd-ae02-4c36-af39-09320a2df06d.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154637396-9d4ce32d-b670-41d6-a929-0849eb33606c.jpg" width=30% height=30%>
<br/>

##### Update Password
<p align = "justify">  They can reset their password by clicking on Change Password.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154639864-c0cd0e37-f0c7-4eb8-9883-955a65fd5aca.jpg" width=30% height=30%>
<br/>

##### Upload Documents
<p align = "justify">  The organization can browse and upload the images of the documents which shows them as a registered organization. An organization has to upload the documents for its surety that this organization is approved by Govt. of India. After this upload part, the admin will approve the documents and verify the organization for becoming an asset of the Sevaarth application.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154640010-efd35434-ff3e-4060-bab5-f643859d6df5.jpg" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154640020-b4276fa4-6952-4bad-8ae2-7906c318d39d.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154640027-72e5db1c-f1d0-4db5-a18c-9b4d3cb8628d.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154640053-e131ebb9-6e80-48bf-b68a-a8729af1addb.jpg" width=30% height=30%>  
<br/>

#### List of Donations and Details
<p align = "justify">  Here the user can have a look at all the previous and current donations done till now. <p> <br/>
  
##### Previous Donations
<p align = "justify">  Here the list of all the Previous donations will be displayed - Name of Donor,Things Donated, and Date on which Donation happened.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154641582-d63a460a-4c59-46b3-8a7e-dac20b77172a.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154645518-544b2362-e0c2-4a2f-9841-0b0ba73fbfb2.jpg" width=30% height=30%> <br/>

##### Current Donations
<p align = "justify">  Here the list of all the current donations will be displayed - Name of Donor, Things to be Donated, and Date on which donation started.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154641571-939ee8ce-1ca1-4bad-8d97-6f93f45912d2.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154645525-ffbf98e8-05c6-4a6a-b159-561b04cc6be7.jpg" width=30% height=30%> <br/>

#### Checking Events and Adding in Calendar
<p align = "justify">  Showcasing the list of all the created events on the recycler view. On click of events, the calendar is opening where the user can add events in the calendar. <p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154637002-edf2e02b-7730-4e4b-b468-e0fe015dd9a3.jpg" width=30% height=30%>    <img src="https://user-images.githubusercontent.com/43794593/154637019-69331bbf-e7a5-468e-970e-5fce7d28568d.jpg" width=30% height=30%>      <img src="https://user-images.githubusercontent.com/43794593/154637030-73ba0243-72b4-48b2-a431-ceee9ec7f55c.jpg" width=30% height=30%>  
<br/>

#### Ratings to Donors (For tracking fake donor)
<p align = "justify">  An organization can give a rating to the donor for their donation after receiving the donation. So that every donor has a profile for further donation in any other or same organization.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154645372-28847520-8982-4e13-9b59-1f0bfc096ec2.jpg" width=30% height=30%>  
<br/>


### FAQ for Sevaarth
<p align = "justify">  We have made an activity called FAQ for Sevaarth so that any user can get information about the Sevaarth application.<p> <br/>
<img src="https://user-images.githubusercontent.com/43794593/154640359-a115a99d-8ad5-47b7-8c97-0280940d241f.jpg" width=30% height=30%>     <img src="https://user-images.githubusercontent.com/43794593/154640373-09fd4ad5-accd-4755-9b59-11a56c892c6d.jpg" width=30% height=30%>        <img src="https://user-images.githubusercontent.com/43794593/154640379-62db136d-42f1-4a1a-8ebc-bab8f68ddf35.jpg" width=30% height=30%> 
<br/>


