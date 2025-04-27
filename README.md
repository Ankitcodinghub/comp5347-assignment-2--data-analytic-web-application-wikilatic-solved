# comp5347-assignment-2--data-analytic-web-application-wikilatic-solved
**TO GET THIS SOLUTION VISIT:** [COMP5347 Assignment 2- Data Analytic Web Application (WikiLatic) Solved](https://www.ankitcodinghub.com/product/comp5347-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120201&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5347 Assignment 2- Data Analytic Web Application (WikiLatic)  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Introduction

In this assignment, you will work as a group to build a small data analytic web application. Each group can have three members. You will demonstrate that you are able to design and implement a typical three-tiered web application. You will also show that your application can communicate with third party web site through published web services.

Dataset

The main dataset contains a number of files in JSON formats storing revision histories of Wikipedia articles. The dataset was created by querying wikipedia API . The articles are selected from Featured Articles .

• title: stores the title of the article

• user: stores the user name or IP address of the user that made the revision

• anon: the presence of the field indicates that the revision is made by anonymous users.

Explanation of other properties can be found from corresponding MediaWiki API document at this page

Below are examples of two typical revision objects:

[

{

“revid”: 827326552,

“parentid”: 827320601,

“minor”: “”,

“user”: “Ohnoitsjamie”,

“size”: 209610,

“sha1”: “9cdb3cffb3f6c751639d23d9f6b4859ba1d9f3d0”,

“parsedcomment”: “…”,

“title”: “San Francisco”

},

{

“revid”: 827320601,

“parentid”: 827029197,

“user”: “65.31.169.21”,

“anon”: “”,

“size”: 209630,

“sha1”: “fd694a124237ad8d2822eb774303e9dc93ca9c54”,

“parsedcomment”: “…”,

“title”: “San Francisco”

},

…

]

Both revisions are from an article with title “San Francisco”. The first revision is made by a registered user with name “Ohnoitsjamie”. The second revision is made by an anonymous user as indicated by the presence of property ‘anon’. The value of ‘user’ property is an IP address.

The dataset also contains two extra text files: admin.txt and bot.txt. The admin.txt file contains a list of all administrators in English Wikipedia. The bot.txt contains a list of all bot users in English Wikipedia. Administrators can perform special actions on wiki pages, some of which are recorded as revisions. The bot users have registered names, but are not human editors. They are scripts designed for automatic tasks, such as fixing grammatical errors or detecting vandalism. Many bot user’s actions would result in new revisions.

Functional Requirements

Main/Landing Page

The Landing page should display key information about the application, WikiLatic, in the form of text and images; e.g., description of the available functionality with some sample analytics graphs that can be generated through the application. Also, it should provide two options; Sign-up and Login. Users cannot access or use available analytics functions until they create a valid account and login.

All users must sign-up before they can see and interact with the application functionality. So, your application should allow users to create an account first. The user must provide first name and last name, email address, username, and password. You need to do appropriate data validation to ensure valid data is entered before creating an account. You do not need to implement any verification for the sign-up process. Once all data is entered correctly, an account should be created and maintained in the database.

Once an account is created successfully, a user should be able to login using their user name and password. Users should be able to see and interact with the analytics functionality only upon successful login.

Wiki Analytics Functions

Your application should compute various analytics at overall data set level and at individual article level.

Overall Analytics

For overall analytics, you need to find out and display the following as text:

• Titles of the three articles with highest number of revisions. This is the default behavior.

• Titles of the three articles with lowest number of revisions. This is the default behavior.

• The user should be provided with a way to change the number of articles for highest and lowest number of revisions, the same number should be applied to both categories.

• The article edited by largest group of registered users. Each wiki article is edited by a number of users, some making multiple revisions. The number of unique users is a good indicator of an article’s popularity.

• The article edited by smallest group of registered users.

• The top 3 articles with the longest history (measured by age). For each article, the revision with the smallest timestamp is the first revision, indicating the article’s creation time. An article’s age is the duration between now and its creation time.

• Article with the shortest history (measured by age).

Beside the above functionality, you also need to show:

• A bar chart of revision number distribution by year and by user type across the whole dataset. Figure 1 shows an example.

• A pie chart of revision number distribution by user type across the whole data set. Figure 2 shows an example.

Figure 1: Example bar chart showing overall yearly revision number distribution

Figure 2: Example pie chart of revision number distribution by user type

We are interested in four types of users: anonymous, administrator, bot and regular user. Revisions made by anonymous users are indicated by the “anon” field in the revision JSON object. Revisions without “anon” field can be made by the other three types of users. You will need to compare the user name with the names in the two text files to determine if a user is administrator, bot or just regular ones.

The text summary should always be displayed on the page in “Overall” state. You should provide a way for an end user to switch between the two charts. This could be a button or a link.

Individual Article Analytics

There should be a message indicating if a data pulling request is made and if so, how many new revisions have been downloaded. It is possible that a data pulling request is made, but the article has no new revision to be downloaded.

For the selected article, display the following summary information:

• The title

• The total number of revisions

• The top 5 regular users ranked by total revision numbers on this article, and the respective revision numbers.

You also need to produce three charts:

• A bar chart of revision number distributed by year and by user type for this article.

• A pie chart of revision number distribution based on user type for this article.

• A bar chart of revision number distributed by year made by one or a few of the top

5 users for this article.

For the last chart, make sure you provide a way to select the users.

Figure 3 shows an example of the yearly revision distribution using data in file

“Germany.json”. Figure 4 shows a pie chart of user type distribution for article “Germany”. Figure 5 shows a bar chart of the year revision distribution of user “Horstschlaemma” for article “Germany”.

The charts should not be displayed in one page, you should provide a mechanism for end users to switch among charts.

Figure 3: Example bar chart showing yearly revision number distribution

Figure 4: Example Pie chart showing user type distribution

Figure 5: Example single user yearly revision distribution

Author Analytics

In this page, you should enable the end user to display all articles that are changed (or have revisions made) by a specific author. To do so, you should allow the end user to an author name in a free text format.

You should display the articles’ names along with number of revisions made by that author next to it. The end user should also be able to select to see time stamps of all revisions made to an article, if that author made more than revision to an article he is attributed with.

Design and Implementation Requirements

You application should operate on a single page, with all communications between client and server happen in asynchronous style. For simplicity, it is allowed to implement the main/landing page functions in a separate page. The other functions (overall, individual and author analytics) must be implemented within a single page (following SPA principles).

You should design your own layout. You should use the MVC pattern to structure your application and interaction among components. The design and UI interfaces should be user-friendly and intuitive.

You should use JavaScript to implement both front and back end of the application. The back-end application should use Node.js framework. The back-end storage system should be MongoDB. You are allowed to use other popular JavaScript libraries not covered in this course.

Deliverable and Submission Guideline

• Source code submission

• System Demo
