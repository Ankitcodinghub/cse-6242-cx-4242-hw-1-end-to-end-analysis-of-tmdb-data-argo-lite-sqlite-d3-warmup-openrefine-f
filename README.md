# cse-6242-cx-4242-hw-1-end-to-end-analysis-of-tmdb-data-argo-lite-sqlite-d3-warmup-openrefine-f
**TO GET THIS SOLUTION VISIT:** [CSE 6242/CX 4242:HW 1: End-to-end analysis of TMDb data, Argo-Lite, SQLite, D3 Warmup, OpenRefine, F](https://www.ankitcodinghub.com/product/cse-6242-cx-4242hw-1-end-to-end-analysis-of-tmdb-data-argo-lite-sqlite-d3-warmup-openrefine-flask-solved-copy/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89690&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 6242\/CX 4242:HW 1: End-to-end analysis of TMDb data, Argo-Lite, SQLite, D3 Warmup, OpenRefine, Flask Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
<strong>Download the </strong><a href="https://poloclub.github.io/cse6242-2021spring-online/hw1/Y7b5hemF5P_hw1.zip"><strong>HW1 Skeleton</strong></a> <strong>before you begin.</strong>

<h1>Homework Overview</h1>
Vast amounts of digital data are generated each day, but raw data are often not immediately “usable”. Instead, we are interested in the information content of the data: what patterns are captured? This assignment covers a few useful tools for acquiring, cleaning, storing, and visualizing datasets.

In Question 1 (Q1), you will collect data using an API for <em>The Movie Database</em> (TMDb). You will construct a graph representation of this data that will show which actors have acted together in various movies, and use <em>Argo Lite</em> to visualize this graph and highlight patterns that you find. This exercise demonstrates how visualizing and interacting with data can help with discovery.

In Q2, you will construct a TMDb database in SQLite, with tables capturing information such as how well each movie did, which actors acted in each movie, and what the movie was about. You will also partition and combine information in these tables in order to more easily answer questions such as “which actors acted in the highest number of movies?”.

In Q3, you will visualize temporal trends in movie releases, using a JavaScript-based library called D3. This part will show how creating interactive rather than static plots can make data more visually appealing, engaging and easier to parse.

Data analysis and visualization is only as good as the quality of the input data. Real-world data often contain missing values, invalid fields, or entries that are not relevant or of interest. In Q4, you will use OpenRefine to clean data from Mercari, and construct GREL queries to filter the entries in this dataset.

Finally, in Q5, you will build a simple web application that displays a table of TMDb data on a single-page website. To do this, you will use Flask, a Python framework for building web applications that allows you to connect Python data processing on the back end with serving a site that displays these results.

<h1>Q1 [40 points] Collect data from TMDb and visualize co-actor network</h1>
Q1.1 [30 points] Collect data from TMDb and build a graph

&nbsp;

For this Q1.1, you will be using and submitting a python file<strong>.</strong> Complete all tasks according to the instructions found in <strong>submission.py </strong>to complete the Graph class, the TMDbAPIUtils class, and the two global functions. The Graph class will serve as a re-usable way to represent and write out your collected graph data. The TMDbAPIUtils class will be used to work with the TMDB API for data retrieval.

&nbsp;

<strong>NOTE:</strong> You <strong>must</strong> only use a version of Python ≥ 3.7.0 and &lt; 3.8 for this question. This question has been developed, tested for these versions. You <strong>must not</strong> use any other versions (e.g., Python 3.8). While we want to be able to extend to more Python versions, the specified versions are what we can definitively support at this time.

&nbsp;

<strong>NOTE:</strong> You must only use the modules and libraries provided at the top of <strong>submission.py</strong> and modules from the <a href="https://docs.python.org/3/library/">Python Standard Library</a><a href="https://docs.python.org/3/library/">.</a> <a href="https://pandas.pydata.org/">Pandas</a> and <a href="https://numpy.org/">Numpy</a> <strong>CANNOT</strong> be used — while we understand that they are useful libraries to learn, completing this question is not critically dependent on their functionality. In addition, to enable our TAs to provide better, more consistent support to our students, we have decided to focus on the subset of libraries.

&nbsp;

<strong>NOTE:</strong> We will call each function once in <strong>submission.py</strong> during grading.&nbsp; The total runtime of submission.py must not exceed 10 minutes. Submissions exceeding this limit will receive <strong>zero</strong> credit. The average runtime of the code during grading is expected to take approximately 4 seconds.&nbsp; When we grade, we will take into account what your code does, and aspects that may be out of your control. For example, sometimes the server may be under heavy load, which may significantly increase the response time (e.g., the closer it is to HW1 deadline, likely the longer the response time!).

&nbsp;

<ol>
<li>[10 pts] Implementation of the Graph class according to the instructions in <strong>py</strong></li>
</ol>
&nbsp;

<ol>
<li>[10 pts] Implementation of the TMDbAPIUtils class according to the instructions in <strong>py. </strong>You will use version 3 of the TMDb API to download data about actors and their co-actors. To use the TMDb API:
<ul>
<li>Create a TMDb account and obtain your client id / client secret which are required to obtain an authentication Token. Refer to <a href="https://poloclub.github.io/cse6242-2021spring-online/hw1/7urMEMxDF8_tmdb_registration_instructions.pdf">this</a> document for detailed instructions (log in using your</li>
</ul>
</li>
</ol>
GT account).

<ul>
<li>Refer to the <a href="https://developers.themoviedb.org/3/getting-started/introduction">TMDB API Documentation</a> as you work on this question. The documentation contains a helpful ‘try-it-out’ feature for interacting with the API calls.</li>
</ul>
&nbsp;

<ol>
<li>[10 pts] Producing correct <strong>csv</strong> and <strong>edges.csv.</strong> You must upload your <strong>nodes.csv</strong> and <strong>edges.csv</strong> files to Argo-Lite as directed in Q1.2.</li>
</ol>
&nbsp;

<strong>NOTE:</strong> Q1.2 builds on the results of Q1.1

Q1.2 [10 points] Visualizing a graph of co-actors using Argo-Lite

Using Argo Lite, visualize a network of actors and their co-actors.

You will produce an Argo Lite graph snapshot your <strong>edges.csv</strong> and <strong>nodes.csv</strong> from Q1.1.c.

&nbsp;

<ol>
<li>To get started, review <a href="https://github.com/poloclub/argo-graph-lite">Argo Lite’s readme on</a> <a href="https://github.com/poloclub/argo-graph-lite">GitHub</a><a href="https://github.com/poloclub/argo-graph-lite">.</a> Argo Lite has been open-sourced.</li>
</ol>
&nbsp;

<ol>
<li>Importing your Graph
<ul>
<li>Launch <a href="https://poloclub.github.io/argo-graph-lite/">Argo Lite</a></li>
<li>From the menu bar, click ‘Graph’ → ‘Import CSV’. In the dialogue that appears:</li>
</ul>
</li>
</ol>
o Select ‘I have both nodes and edges file’

<ul>
<li>Under Nodes, use ‘Choose File’ to select <strong>csv</strong> from your computer o Leave ‘Has Headers’ selected o Verify ‘Column for Node ID’ is ‘id’</li>
<li>Under Edges, use ‘Choose File’ to select <strong>csv</strong> from your computer o Verify ‘Column for Source ID’ is ‘source’ o Select ‘Column for Target ID’ to ‘target’ o Verify ‘Selected Delimiter’ is ‘,’</li>
<li>At the bottom of the dialogue, verify that ‘After import, show’ is set to ‘All Nodes’</li>
<li>The graph will load in the window. Note that the layout is paused by default; you can select to ‘Resume’ or ‘Pause’ layout as needed.</li>
<li>Dragging a node will ‘pin’ it, freezing its position. Selecting a pinned node, right clicking it, then choosing ‘unpin selected’ will unpin that node, so its position will once again be computed by the graph layout algorithm.&nbsp; Experiment with pinning and unpinning nodes.</li>
</ul>
&nbsp;

<strong>NOTE:</strong> If a malformed .csv is uploaded, Argo-Lite could become un-responsive. If you suspect this is the case, open the developer tools for your browser and review any console error messages.

&nbsp;

<ol>
<li>[7 points] Setting graph display options</li>
</ol>
<ul>
<li>On “Graph Options” panel, under ‘Nodes’ → ‘Modifying All Nodes’, expand ‘Color’ menu o Select Color by ‘degree’, with scale: ‘Linear Scale’
<ul>
<li>Select a color gradient of your choice that will assign lighter colors to nodes with higher node degrees, and darker colors to nodes with lower degrees ● Collapse the ‘Color’ options, expand the ‘Size’ options.</li>
<li>Select ‘Scale by’ to ‘degree’, with scale: Linear Scale’ o Select meaningful Size Range values of your choice or use the default range.</li>
</ul>
</li>
<li>Collapse the ‘Size’ options</li>
<li>On the Menu, click ‘Tools’ → ‘Data Sheet’ ● Within the ‘Data Sheet’ dialogue:
<ul>
<li>Click ‘Hide All’</li>
<li>Set ‘10 more nodes with highest degree’ o Click ‘Show’ and then close the ‘Data Sheet’ dialogue</li>
</ul>
</li>
<li>Click and drag a rectangle selection around the visible nodes</li>
<li>With the nodes selected, configure their node visibility by setting the following:
<ul>
<li>Go to ‘Graph Options’ → ‘Labels’ o Click ‘Show Labels of Selected Nodes’</li>
<li>At the bottom of the menu, select ‘Label By’ to ‘name’</li>
<li>Adjust the ‘Label Length’ so that the full text of the actor name is displayed</li>
</ul>
</li>
<li>Show only non-leaf vertices. On the Menu, click ‘Tools’ → Data Sheet→ ‘Show <em>k</em> More Nodes with Highest Degree’. (where <em>k</em> is the input number of nodes such that <strong>only nodes with a degree &gt; 1 are visible</strong>).&nbsp; To make this easier, we suggest writing a utility function in your Graph class to find the count of leaf nodes in order to determine how many nodes should be shown. <em>&nbsp;</em></li>
</ul>
&nbsp;

The result of this workflow yields a graph with the sizing and coloring depend upon the node degree and the nodes with the highest degree are emphasized by showing their labels.&nbsp; Also,

&nbsp;

<ol>
<li>[3 points] Designing a meaningful graph layout</li>
</ol>
Using the following guidelines, create a visually meaningful and appealing layout:

<ul>
<li>Reduce as much edge crossing as possible</li>
<li>Do not allow any nodes to overlap</li>
<li>Keep the graph compact and symmetric as possible</li>
<li>Use the nodes’ spatial positions to convey information (e.g., “clusters” or groups)</li>
<li>Experiment with showing additional node labels. If showing all node labels creates too much visual complexity, show at least 10 “important” node labels. You may decide what “importance” mean to you. For example, you may consider nodes (actors) having higher connectivity as potentially more “important” (based on how the graph is built).</li>
</ul>
&nbsp;

The objective of this task is to familiarize yourself with basic, important graph visualization features. Therefore, this is an <strong>open-ended task</strong> and most designs are acceptable&nbsp; You should experiment with Argo Lite’s features, changing node size and shape, etc. In practice, it is not possible to create “perfect” visualizations for most graph datasets. The above guidelines are ones that generally help. However, like most design tasks, creating a visualization is about making selective design compromises. Some guidelines could create competing demands and following all guidelines may not guarantee a “perfect” design.

&nbsp;

If you want to save your Argo Lite graph visualization snapshot locally to your device, so you can continue working on it later, we recommend the following workflow.

<ul>
<li>Select ‘Graph’ → ‘Save Snapshot’ o In the ‘Save Snapshot` dialog, click ‘Copy to Clipboard’
<ul>
<li>Open an external text editor program such as TextEdit or Notepad. Paste the clipboard contents of the graph snapshot, and save it to a file with a <strong>.json</strong>&nbsp; You should be able to accomplish this with a default text editor on your computer by overriding the default file extension and manually entering ‘.json’.</li>
<li>You may save your progress by saving the snapshot and loading them into Argo Lite to continue your work.</li>
<li>To load a snapshot, choose ‘Graph’ → ‘Open Snapshot’ ● Select the graph snapshot you created.</li>
</ul>
</li>
</ul>
&nbsp;

<strong>NOTE:</strong> Q1.2 (d) will not be graded on Gradescope.&nbsp; We will give a qualitative score on the overall design and presentation of your graph visualization in Argo Lite.

&nbsp;

<ol>
<li>Publish and Share your graph snapshot
<ul>
<li>Name your graph: On the top navigation bar, click on the label ‘Untitled Graph’. In the ‘Rename Snapshot’ dialogue window that appears, enter your GTUsername as the ‘Snapshot Name’ and click ‘Done’</li>
<li>Select ‘Graph ‘ → ‘Publish and Share Snapshot’ → ‘Share’</li>
<li>Next, click ‘Copy to Clipboard’ to copy the generated URL</li>
<li>Return the URL in the return_argo_lite_snapshot() function in <strong>py</strong> If you modify your graph after you publish and share a URL, you will need to re-publish and obtain a new URL of your latest graph. Only the graph snapshot shared via the URL will be graded.</li>
</ul>
</li>
</ol>
&nbsp;

<strong>NOTE:</strong> If this function returns a malformed or invalid snapshot URL, it will likely cause Gradescope to crash.

&nbsp;

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Deliverables:</strong>&nbsp; Submit the following file to Gradescope:<strong>submission.py</strong>: the completed Python file

<h1>Q2 [35 points] SQLite</h1>
<a href="http://www.sqlite.org/">SQLite</a> is a lightweight, serverless, embedded database that can easily handle multiple gigabytes of data. It is one of the world’s most popular embedded database systems. It is convenient to share data stored in an SQLite database — just one cross-platform file which does not need to be parsed explicitly (unlike CSV files, which have to be parsed).

&nbsp;

You will modify the given <strong>Q2_SQL.py </strong>file by adding SQL statements to it. We suggest that you consider testing your SQL locally on your computer using interactive tools to speed up testing and debugging, such as DB Browser for SQLite <a href="https://sqlitebrowser.org/">(</a><a href="https://sqlitebrowser.org/">https://sqlitebrowser.org</a><a href="https://sqlitebrowser.org/">)</a>.

&nbsp;

&nbsp;

<strong>NOTE:</strong> You <strong>must</strong> only use a version of Python ≥ 3.7.0 and &lt; 3.8 for this question. This question has been developed, tested for these versions. You <strong>must not</strong> use any other versions (e.g., Python 3.8). The Autograder is using SQLite release 3.22.

&nbsp;

<strong>NOTE: </strong>Do not modify the import statements, everything you need to complete this question has been imported for you. You may not use other libraries for this assignment.

&nbsp;

<strong>NOTE:</strong> A Sample class has been provided for you to see some sample SQL statements, you can turn off this output by changing the global variable SHOW to False. This <strong>must </strong>be set to <em>false</em> before uploading to Gradescope.

&nbsp;

<strong>GTusername</strong> – Please update the method GTusername with your credentials

&nbsp;

<strong>NOTE: </strong>For the questions in this section, you must only use <a href="https://www.w3schools.com/sql/sql_join_inner.asp">INNER JOIN</a> when performing a join between two tables. Other types of joins may result in incorrect results.

&nbsp;

<ol>
<li>[9 points] <em>Create tables and import data</em>.
<ol>
<li>[2 points] Create two tables (via two separate methods, part_ai_1 and part_ai_2, respectively in Q2_SQL.py) named movies and movie_cast with columns having the indicated data types:
<ol>
<li>movies
<ol>
<li>id (integer) 2. title (text)</li>
<li>score (real)</li>
</ol>
</li>
<li>movie_cast
<ol>
<li>movie_id (integer)</li>
<li>cast_id (integer)</li>
<li>cast_name (text)</li>
<li>birthday (text)</li>
<li>popularity (real)</li>
</ol>
</li>
</ol>
</li>
</ol>
</li>
</ol>
&nbsp;

<ol>
<li>[2 points] Import the provided <strong>csv</strong> file into the movies table and <strong>movie_cast.csv</strong> into the movie_cast table
<ol>
<li>You will write Python code that imports the .csv files into the individual tables. This will include looping though the file and using the <strong>‘INSERT INTO’</strong> SQL command. Only use relative paths while importing files since absolute/local paths are specific locations that exist only on your computer and will cause the auto-grader to fail.</li>
</ol>
</li>
</ol>
&nbsp;

<ul>
<li>[5 points]<em> Vertical Database Partitioning. </em>Database partitioning is an important technique that</li>
</ul>
divides large tables into smaller tables, which may help speed up queries. For this question you will create a new table cast_bio from the movie_cast table (i.e., columns in cast_bio will be a subset of those in movie_cast) Do not edit the movie_cast table. Be sure that when you insert into the new cast_bio that the values are unique. Please read <a href="https://www.sqlshack.com/database-table-partitioning-sql-server/">this page</a> for an example of vertical database partitioning.

cast_bio

<ol>
<li>cast_id (integer)</li>
<li>cast_name (text)</li>
<li>birthday (date)</li>
<li>popularity (real)</li>
</ol>
&nbsp;

<ol>
<li>[1 point] <em>Create indexes.</em> Create the following indexes for the tables specified below. This step increases the speed of subsequent operations; though the improvement in speed may be negligible for this small database, it is significant for larger databases.</li>
<li>movie_index for the id column in movies table ii. cast_index for the cast_id column in movie_cast table iii. cast_bio_index for the cast_id column in cast_bio table</li>
</ol>
&nbsp;

<ol>
<li>[3 points] <em>Calculate a proportion</em>. Find the proportion of movies having a score &gt; 50 and that has ‘war’ in the name. Treat each row as a different movie. The proportion should only be based on the total number of rows in the movie table. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a> Do <strong>NOT</strong> use the</li>
</ol>
ROUND() function as it does not work the same on every OS.

&nbsp;

Output format and sample value:

7.70

<strong>&nbsp;</strong>

<ol start="10">
<li>[4 points] <em>Find the most prolific actors</em>. List 5 cast members with the highest number of movie appearances that have a popularity &gt; 10. Sort the results by the number of appearances in descending order, then by cast_name in alphabetical order.</li>
</ol>
&nbsp;

Output format and sample values (cast_name,appearance_count):

Harrison Ford,2

&nbsp;

<ol>
<li>[4 points] <em>Find the highest scoring movies with the smallest cast</em>. List the 5 highest-scoring movies that have the fewest cast members. Sort the results by score in descending order, then by number of cast members in ascending order, then by movie name in alphabetical order. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a></li>
</ol>
&nbsp;

Output format and sample values (movie_title,movie_score,cast_count):

Star Wars: Holiday Special,75.01,12&nbsp; War Games,58.49,33

&nbsp;

&nbsp;

<ol>
<li>[4 points] <em>Get high scoring actors.</em> Find the top ten cast members who have the highest average movie scores. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a>
<ul>
<li>Sort the output by average score in descending order, then by cast_name in alphabetical order.</li>
<li>Do not include movies with score &lt;25 in the average score calculation. ▪ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exclude cast members who have appeared in two or fewer movies.</li>
</ul>
</li>
</ol>
&nbsp;

Output format and sample values (cast_id,cast_name,average_score):

8822,Julia Roberts,53.00

<ol start="40">
<li>[6 points]<em> Creating views. </em><a href="https://sqlite.org/lang_createview.html">Create a view</a> <a href="https://www.w3schools.com/sql/sql_view.asp">(</a><a href="https://www.w3schools.com/sql/sql_view.asp">virtual table</a><a href="https://www.w3schools.com/sql/sql_view.asp">)</a> called good_collaboration that lists pairs of actors who have had a good collaboration as defined here. Each row in the view describes one pair of actors who appeared in at least 3 movies together AND the average score of these movies is &gt;= 40.</li>
</ol>
&nbsp;

The view should have the format: good_collaboration( cast_member_id1, cast_member_id2, movie_count, average_movie_score)

&nbsp;

For symmetrical or mirror pairs, only keep the row in which cast_member_id1 has a lower numeric value. For example, for ID pairs (1, 2) and (2, 1), keep the row with IDs (1, 2). There should not be any “self pair” where the value of cast_member_id1 is the same as that of cast_member_id2.

&nbsp;

<strong>NOTE</strong><strong>: Full points will only be awarded for queries that use joins for part g.</strong>

<strong>&nbsp;</strong>

Remember that creating a view will not produce any output, so you should test your view with a few simple select statements during development. One such test has already been added to the code as part of the auto-grading.

&nbsp;

<strong>NOTE</strong><strong>: Do not submit any code that creates a ‘TEMP’ or ‘TEMPORARY’ view that you may have used for testing.</strong>

&nbsp;

<strong>Optional Reading:</strong> <a href="http://stackoverflow.com/questions/1278521/why-do-you-create-a-view-in-a-database">Why</a> <a href="http://stackoverflow.com/questions/1278521/why-do-you-create-a-view-in-a-database">create views?</a>

&nbsp;

<ol start="2">
<li>[4 points]<em> Find the best collaborators. </em>Get the 5 cast members with the highest average scores from the good_collaboration view, and call this score the collaboration_score. This score is the average of the average_movie_score corresponding to each cast member, including actors in cast_member_id1 as well as cast_member_id2. Format all decimals to two places <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">using</a> <a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">printf()</a><a href="https://stackoverflow.com/questions/9149063/sqlite-format-number-with-2-decimal-places-always">.</a></li>
</ol>
<ul>
<li>Sort your output by collaboration_score in descending order, then by cast_name alphabetically.</li>
</ul>
Output format (cast_id,cast_name,collaboration_score):

2,Mark Hamil,99.32

1920,Winoa Ryder,88.32

&nbsp;

<ol>
<li>[4 points] SQLite supports simple but powerful Full Text Search (FTS) for fast text-based querying (<a href="https://www.sqlite.org/fts3.html">FTS</a> <a href="https://www.sqlite.org/fts3.html">documentation</a><a href="https://www.sqlite.org/fts3.html">)</a>. Import movie overview data from the <strong>csv</strong> into a new FTS table called movie_overview with the schema:</li>
</ol>
&nbsp;

movie_overview

▪ id (integer) ▪ overview (text)

&nbsp;

<strong>NOTE:</strong> Create the table using <strong>fts3</strong> or <strong>fts4</strong> only. Also note that keywords like NEAR, AND, OR and NOT are case sensitive in FTS queries.

&nbsp;

<ol>
<li>[1 point] Count the number of movies whose overview field contains the word ‘fight’. Matches are not case sensitive. Match full words, not word parts/sub-strings.</li>
</ol>
e.g., Allowed: ‘FIGHT’, ‘Fight’, ‘fight’, ‘fight.’.&nbsp; Disallowed: ‘gunfight’, ‘fighting’, etc.

&nbsp;

Output format:

12

<ol>
<li>[2 points] Count the number of movies that contain the terms ‘space’ and ‘program’ in the overview field with no more than 5 intervening terms in between. Matches are not case sensitive. As you did in h(i)(1), match full words, not word parts/sub-strings. e.g., Allowed: ‘In Space there was a program’, ‘In this space program’. Disallowed: ‘In space you are not subjected to the laws of gravity. A program.’, etc.</li>
</ol>
&nbsp;

&nbsp;

Output format:

6

&nbsp;

<strong>Deliverables:</strong> <strong>Submit the following file to Gradescope </strong>

&nbsp;

<ol>
<li><strong>Q2_SQL.py</strong>: Modified file containing all the SQL statements you have used to answer parts a – h in the proper sequence.</li>
</ol>
&nbsp;

<h1>Q3 [15 points] D3 (v5) Warmup</h1>
<strong>Read chapters 4-8 of Scott Murray’s </strong><a href="https://learning.oreilly.com/library/view/interactive-data-visualization/9781491921296/ch04.html#setup-chapter4"><strong>Interactive Data Visualization for the Web, 2nd edition</strong></a> (sign in using your GT account, e.g., jdoe3@gatech.edu). You may also briefly review chapters 1-3 if you need additional background on web development. <strong>This simple reading provides important foundation</strong> you will need for Homework 2. This question uses D3 version v5, while the book covers D3 v4. What you learn from the book is transferable to v5. In Homework 2, you will work with D3 extensively.

&nbsp;

<strong>NOTE the following important points: </strong>

&nbsp;

<ol>
<li>We highly recommend that you use the latest Chrome browser to complete this question. We will grade your work using <strong>Chrome 86.0 (or newer)</strong>.</li>
</ol>
&nbsp;

<ol start="2">
<li>For this homework, the D3 library is provided to you in the <strong>lib</strong> You must <strong>NOT</strong> use any D3 libraries (d3*.js) other than the ones provided. In Gradescope, these libraries will be provided for you in the autograding environment.</li>
</ol>
&nbsp;

<ol start="3">
<li>You will need to setup an HTTP server to run your D3 visualizations as discussed in the D3 lecture (OMS students: the video “Week 5 – Data Visualization for the Web (D3) – Prerequisites: JavaScript and SVG”. Campus students: see <a href="https://poloclub.github.io/cse6242-2021spring-campus/slides/CSE6242-500-infovis-stolper.pdf">lecture PDF</a><a href="https://poloclub.github.io/cse6242-2021spring-campus/slides/CSE6242-500-infovis-stolper.pdf">.</a>). The easiest way is to use <a href="https://medium.com/@ryanblunden/create-a-http-server-with-one-command-thanks-to-python-29fcfdcd240e">server</a> for Python 3.x. <strong>Run your local HTTP server in the hw1-skeleton/Q3 folder. </strong></li>
</ol>
&nbsp;

<ol start="4">
<li>We have provided sections of code along with comments in the skeleton to help you complete the implementation. While you do not need to remove them, you may need to write additional code to make things work. <strong>&nbsp;</strong></li>
</ol>
&nbsp;

<ol start="5">
<li>All d3*.js files in the <strong>lib</strong> folder are referenced using <strong>relative paths</strong> in your html file. For example, since the file “Q3/submission.html” uses d3, its header contains: <strong>&nbsp;</strong><strong>&lt;script&nbsp; type=”text/javascript” src=”lib/d3/d3.min.js”&gt;&lt;/script&gt; It is incorrect to use an absolute path such as:</strong></li>
</ol>
&lt;script type=”text/javascript” src=”http://d3js.org/d3.v5.min.js”&gt;&lt;/script&gt;

&nbsp;

The 3 files that are referenced are:

<ul>
<li>lib/d3/d3.min.js</li>
<li>lib/d3-dsv/d3-dsv.min.js</li>
<li>lib/d3-fetch/d3-fetch.min.js</li>
</ul>
<ol start="6">
<li>In your html / js code<strong>, </strong>use a <strong>relative path</strong> to read in the dataset file<strong>.</strong> For example, since Q3 requires reading data from the csv file, the path should be ‘q3.csv’ and <strong>NOT</strong> an absolute path such as “C:/Users/polo/HW1skeleton/Q3/q3.csv”. Absolute/local paths are specific locations that exist only on your computer, which means your code will <strong>NOT</strong> run on our machines when we grade (and you will lose points). Gradescope will provide a copy of the q3.csv dataset using the same directory structure provided in the HW skeleton.</li>
</ol>
&nbsp;

<ol start="7">
<li>Load the data from csv using D3 fetch methods. We recommend d3.dsv(). Handle any data conversions that might be needed, <em>e.g., </em>strings that need to be converted to integer. See <a href="https://github.com/d3/d3-fetch#dsv">https://github.com/d3/d3</a><a href="https://github.com/d3/d3-fetch#dsv">–</a><a href="https://github.com/d3/d3-fetch#dsv">fetch#dsv</a></li>
</ol>
<strong>submission.html</strong> : when run in a browser, it should display a vertical barplot with the following specifications:

<ol start="3">
<li>[3.5 points] The barplot must display one bar per row in the csv dataset. Each bar corresponds to the running total of movies for a given year.&nbsp; The height of each bar represents the running total.&nbsp; The bars are ordered by ascending time with the earliest observation at the far left.&nbsp; i.e., 1880, 1890,</li>
</ol>
…, 2000

<ol>
<li>[1 point] The bars must have the same fixed width, and there must be some space between two bars, so that the bars do not overlap.</li>
<li>[3 points] The plot must have visible X and Y axes that scale according to the generated bars. That is, the axes are driven by the data that they are representing. Likewise, the ticks on these axes must adjust automatically based on the values within the datasets, i.e., they must not be hard-coded. The x-axis must be a &lt;g&gt; element having the id: “x_axis” and the y-axis must be a &lt;g&gt; element having the id: “y_axis”.</li>
<li>[2 points] Set x-axis label to ‘Year’ and y-axis label to ‘Running Total’. The x-axis label must be a &lt;text&gt; element having the id: “x_axis_label” and the y-axis label must be a &lt;text&gt; element having the id: “y_axis_label”.</li>
<li>[1 point] Use a linear scale for the Y axis to represent the running total (recommended function:</li>
</ol>
d3.scaleLinear()).

<ol>
<li>[3 points] Use a time scale for the x-axis to represent year (recommended function:</li>
</ol>
d3.scaleTime()).&nbsp; It may be necessary to use time parsing / formatting when you load and display the year data. The axis would be overcrowded if you display every year value so set the xaxis ticks to display one tick for every 10 years.

<ol>
<li>[1 point] Set the HTML title tag and display a title for the plot. Set the HTML title tag (i.e., &lt;title&gt;</li>
</ol>
Running Total of TMDb Movies by Year &lt;/title&gt;). Position the title “Running Total of TMDb Movies by Year” above the barplot.&nbsp; The title must be a &lt;text&gt; element having the id: “title”

<ol>
<li>[0.5 points] Add your GT username (usually includes a mix of letters and numbers) to the area beneath the bottom-right of the plot (see example image). The GT username must be a &lt;text&gt; element having the id: “credit”</li>
</ol>
<ol start="8">
<li>Gradescope will render your plot using Chrome and present you with a Dropbox link to view the screenshot of your plot with the solution plot in both a side by side and an overlay display.</li>
</ol>
&nbsp;

The screenshot visual feedback to you for making adjustments and corrections.&nbsp; This is also an excellent way to identify mistakes, <em>e.g.,</em> a blank plot likely indicates a serious error.&nbsp; It is not necessary to exactly duplicate the solution plot.&nbsp;&nbsp;&nbsp; We recommend the following DOM structure and sizing attributes for accurate comparisons:

&nbsp;

&nbsp;

<strong>Deliverables : Submit the following file to Gradescope: </strong>

<ol>
<li><strong>submission.html</strong>: Modified file containing all html, javascript, and any css code required to produce the barplot. Do not include the D3 libraries or q3.csv dataset.</li>
</ol>
&nbsp;

<h1>Q4 [5 points] OpenRefine</h1>
OpenRefine is a Java application and requires Java JRE to run. Download and install Java if you do not have it (you can verify by typing ‘java -version’ in your computer’s terminal or command prompt).

&nbsp;

<ol start="3">
<li>Watch the videos on <a href="http://openrefine.org/">OpenRefin</a><a href="http://openrefine.org/">e</a><a href="http://openrefine.org/">’</a><a href="http://openrefine.org/">s homepage for an overview of its features.</a> Then, <a href="http://openrefine.org/download.html">download</a> and <a href="https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions">install</a> OpenRefine release 3.3. Do not use version 3.4 (which is in beta status).</li>
</ol>
&nbsp;

<ol>
<li>Import Dataset
<ul>
<li><a href="https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions">Run</a> OpenRefine and point your browser at 127.0.0.1:3333.</li>
<li>We use a products dataset from Mercari, derived from a Kaggle <a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge">competition</a> (Mercari Price Suggestion Challenge). If you are interested in the details, visit the <a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge/data">data description page</a><a href="https://www.kaggle.com/c/mercari-price-suggestion-challenge/data">.</a></li>
</ul>
</li>
</ol>
We have sampled a subset of the dataset provided as “properties.csv”.

<ul>
<li>Choose “Create Project” → This Computer → csv”. Click “Next”.</li>
<li>You will now see a preview of the data. Click “Create Project” at the upper right corner.</li>
</ul>
&nbsp;

<ol>
<li>Clean/Refine the data</li>
</ol>
&nbsp;

<strong>NOTE:</strong> OpenRefine maintains a log of all changes. You can undo changes. Use the “Undo/Redo” button at the upper left corner. Follow the exact output format specified in every part below.

&nbsp;

<ol>
<li>[0.5 point] Select the category_name column and choose ‘Facet by Blank’ (Facet → Customized Facets → Facet by blank) to filter out the records that have blank values in this column. Provide the number of rows that return True in txt. Exclude these rows.</li>
</ol>
&nbsp;

Output format and sample values:

i.rows: 500

&nbsp;

<ol>
<li>[1 point] Split the column category_name into multiple columns without removing the original column. For example, a row with “Kids/Toys/Dolls &amp; Accessories” in the category_name column would be split across the newly created columns as “Kids”, “Toys” and “Dolls &amp; Accessories”. Use the existing functionality in OpenRefine that creates multiple columns from an existing column based on a separator (i.e., in this case ‘/’) and does not remove the original category_name Provide the number of new columns that are created by this operation, excluding the original category_name column.</li>
</ol>
&nbsp;

Output format and sample values:

ii.columns: 10

&nbsp;

<strong>NOTE:</strong> There are many possible ways to split the data. While we have provided one way to accomplish this in step ii, some methods could create columns that are completely empty. In this dataset, none of the new columns should be completely empty. Therefore, to validate your output, we recommend that you verify that there are no columns that are completely empty, by sorting and checking for null values.

iii. [0.5 points] Select the column name and apply the Text Facet (Facet → Text Facet). Cluster by using (Edit Cells → Cluster and Edit …) this opens a window where you can choose different “methods” and “keying functions” to use while clustering. Choose the keying function that produces the smallest number of clusters under the “Key Collision” method. Click ‘Select All’ and ‘Merge Selected &amp; Close’. Provide the name of the keying function and the number of clusters that was produced.

&nbsp;

Output format and sample values:

iii.function: fingerprint, 200

&nbsp;

<strong>NOTE:</strong> Use the default Ngram size when testing Ngram-fingerprint.

&nbsp;

<ol>
<li>[1 point] Replace the null values in the brand_name column with the text “Unknown” (Edit Cells &gt; Transform). Provide the <a href="https://github.com/OpenRefine/OpenRefine/wiki/GREL-String-Functions">General Refine Evaluation Language</a> (GREL) expression used.</li>
</ol>
&nbsp;

Output format and sample values:

iv.GREL_categoryname: endsWith(“food”, “ood”)

&nbsp;

<ol>
<li>[1 point] Create a new column high_priced with the values 0 or 1 based on the “price” column with the following conditions: if the price is greater than 90, high_priced should be set as 1, else 0. Provide the GREL expression used to perform this.</li>
</ol>
&nbsp;

Output format and sample values:

v.GREL_highpriced: endsWith(“food”, “ood”)

&nbsp;

<ol>
<li>[1 point] Create a new column has_offer with the values 0 or 1 based on the</li>
</ol>
item_description column with the following conditions: If it contains the text “discount” or “offer” or “sale”, then set the value in has_offer as 1, else 0. Provide the GREL expression used to perform this. Convert the text to lowercase before you search for the terms.

&nbsp;

Output format and sample values:

vi.GREL_hasoffer: endsWith(“food”, “ood”)

<strong>&nbsp;</strong>

<strong>Deliverables:</strong> <strong>Submit the following files to Gradescope: </strong>

<ul>
<li><strong>csv</strong> : Export the final table as a comma-separated values (.csv) file.</li>
<li><strong>json</strong> : Submit a list of changes made to file in json format. Use the “<em>Extract Operation History</em>” option under the Undo/Redo tab to create this file.</li>
<li><strong>txt </strong>: A text file with answers to parts c.i, c.ii, c.iii, c.iv, c.v, c.vi. Provide each answer in a new line in the exact output format specified. Your file’s final formatting should result in a .txt file that has each answer on a new line followed by one blank line (to help visually separately the answers)</li>
</ul>
<h1>Q5 [5 points] Introduction to Python Flask</h1>
<a href="https://flask.palletsprojects.com/en/1.1.x/">Flask</a> is a lightweight web application framework written in Python that provides you with tools, libraries and technologies to quickly build a web application. It allows you to scale up your application as needed.

&nbsp;

You will modify the given file:

<ul>
<li>wrangling_scripts/wrangling.py</li>
</ul>
<strong>&nbsp;</strong>

<strong>NOTE:</strong> You <strong>must</strong> only use a version of Python ≥ 3.7.0 and &lt; 3.8 for this question. This question has been developed, tested for these versions. You <strong>must not</strong> use any other versions (e.g., Python 3.8).

&nbsp;

<strong>NOTE:</strong> You must only use the modules and libraries provided at the top of <strong>wrangling.py</strong> and modules from the <a href="https://docs.python.org/3/library/">Python Standard Library</a> (except Flask). <a href="https://pandas.pydata.org/">Pandas</a> and <a href="https://numpy.org/">Numpy</a> <strong>CANNOT</strong> be used — while we understand that they are useful libraries to learn, completing this question is not critically dependent on their functionality. In addition, to enable our TAs to provide better, more consistent support to our students, we have decided to focus on the subset of libraries.

&nbsp;

<strong>Username()</strong>– Update the username() method inside wrangling.py by including your GTUsername.

&nbsp;

<ul>
<li>Get started by installing Flask on your machine by running pip install Flask (Note that you can optionally create a virtual environment by following the steps <a href="https://flask.palletsprojects.com/en/1.1.x/installation/#virtual-environments">here</a><a href="https://flask.palletsprojects.com/en/1.1.x/installation/#virtual-environments">.</a> Creating a virtual environment is purely optional and can be skipped.)</li>
</ul>
&nbsp;

<ul>
<li>To run the code, you must navigate to the Q5 folder in your terminal/command prompt and execute the following command: python run.py. After running the command go to <a href="http://127.0.0.1:3001/">http://127.0.0.1:3001/</a> on your browser. This will open up index.html showing a table in which the rows returned by data_wrangling() are displayed.</li>
</ul>
&nbsp;

<ul>
<li>You must solve the following 2 sub-questions:
<ol>
<li>[2 points] Read the top 100 rows using the data_wrangling() method.</li>
</ol>
</li>
</ul>
&nbsp;

<strong>NOTE:</strong> The skeleton code by default reads all the rows from movies.csv. You must add the required code to ensure reading only the <strong>first </strong>100 data rows. The skeleton code already handles reading the table header for you.

&nbsp;

<ol>
<li>[3 points]: Sort the table in <em>descending </em>order of the values i.e., with larger values at the top and smaller values at the bottom of the table in the last (3<sup>rd</sup>) column.</li>
</ol>
&nbsp;

<strong>Deliverables:</strong> <strong>Submit the following file to Gradescope: </strong>

<ul>
<li><strong>wrangling.py </strong>: the completed python file with your changes.</li>
</ul>
<h1><strong>Extremely Important:</strong> Validate submitted files on Gradescope</h1>
We understand that some of you may work on this assignment until just prior to the deadline, rushing to submit your work before the submission window closes.&nbsp; <strong>Please take the time</strong> to validate that <strong>all files</strong> have been submitted for each question and that you have not forgotten to include any deliverables!&nbsp; If a deliverable is not submitted, you will receive <strong>zero </strong>credit for the affected portion of the assignment — this is a very sad way to lose points, since you have already done the work!

&nbsp;

As a final check, verify that you have submitted the following files for each question in Gradescope:

&nbsp;

HW1 – Q1: submission.py HW1 – Q2:

Q2_SQL.py

HW1 – Q3: submission.html

HW1 – Q4: properties_clean.csv changes.json

Q4Observations.txt HW1 – Q5:

wrangling.py
