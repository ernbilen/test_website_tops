## Past Seminars

You can find a list of past seminars with a link to the paper presented and a video recording of the seminar if available.


<table width="100%" cellspacing="5" cellpadding="5">

{% for speaker in site.data.past_seminars %}
<tr>
  <td colspan="2" height="40" valign="top" class="session"><strong>Date: {{ speaker.Date }}</strong></td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Presenter: {{ speaker.Presenter }}</td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Institution: {{ speaker.Institution }}</td>
</tr>
<tr>
  <td colspan="2" height="40" valign="top" class="chair">Presentation Type: {{ speaker.Type }}</td>
</tr>
<tr>
   <td height="30" valign="top" class="paper">Presentation Title: "{{ speaker.Title }}"</td>
</tr>
{% if (speaker.Presenter == 'Armando Meier') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2021)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Leontine Goldzahl') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a></td>
</tr>
{% elsif (speaker.Title == 'Cities and Smoking') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (March 2021)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Kai-Wen Cheng') %}
<tr>
  <td id="kai" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2022)</a></td>

{% elsif (speaker.Presenter == 'Brian King') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.ReadingList }}" download="{{ speaker.ReadingList }}">Panel Questions</a></td>


</tr>
{% elsif (speaker.Presenter == 'Hojin Park') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (January 2025)</a></td>

</tr>
{% elsif (speaker.Presenter == 'Matthew Carpenter') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2023)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Christopher Carpenter') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2021)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Lauren Hoehn-Velasco') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (December 2022)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Dhaval Dave') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (July 2023)</a> </td>
</tr>
{% elsif (speaker.Presenter == 'Chad Cotti') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (December 2024)</a> </td>
</tr>
{% elsif (speaker.Presenter == 'Rahi Abouk') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (March 2024)</a>|<a href="{{ speaker.Paper2}}" download="{{ speaker.Paper2 }}">Supplement #1</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}">Supplement #2</a></td>
</tr>
{% elsif (speaker.Presenter == 'Abigail S. Friedman') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (January 2023)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Catherine Maclean') %}
<tr id="jcm">
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (September 2022)</a></td>
</tr>
{% elsif (speaker.Title == 'Cochrane Living Systematic Review of E-cigarettes for Smoking Cessation') or (speaker.Presenter == 'Aryn Phillips') or (speaker.Presenter == 'Jon Oliver') or (speaker.Presenter == 'Hai Nguyen') or (speaker.Presenter == 'Erica Mtenga') or (speaker.Presenter == 'Marcus Munafo') or (speaker.Presenter == 'Matthew Stone') or (speaker.Presenter == 'Michael Pesko') or (speaker.Presenter == 'Bukola Usidame')  or (speaker.Presenter == 'Andrea Titus') or (speaker.Presenter == 'Vidhura Tennekoon') or (speaker.Presenter == 'Melanie Dove') or (speaker.Presenter == 'Anton Badev') or (speaker.Presenter == 'Hyunchul Kim') or (speaker.Presenter == 'Jasmine Khouja') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'Ali Goli')%}
<tr>
  <td id="rigotti" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a></td>
</tr>
{% elsif (speaker.Title == 'Optimal ecigarette policy when preferences and internalities are correlated') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a>|<a href="{{ speaker.Transcript }}" download="{{ speaker.Transcript }}">Transcript</a></td>
</tr>

{% elsif (speaker.Presenter == 'Katherine Meckel') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}"> Working Paper</a><a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}"> Published Paper (March 2025)</a></td>
</tr>

{% elsif (speaker.Presenter == 'Rizki Siregar') or (speaker.Presenter == 'Dan Sacks') or (speaker.Presenter == 'Ying Yao') or (speaker.Presenter == 'Rachana Bhatt') or (speaker.Presenter == 'Aisha Baisalova') or (speaker.Presenter == 'Chad Cotti') or (speaker.Presenter == 'Vinish Shrestha') or (speaker.Presenter == 'Russell Leonard')  or (speaker.Presenter == 'Kathleen Hui') or (speaker.Presenter == 'Abigail Friedman') or (speaker.Presenter == 'Eye Eoun Jung') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}"> Working Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'Bo Feng') %}
<tr>
  <td id="liber" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}"> Working Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'David Hammond') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a></td>
</tr>

{% elsif (speaker.Presenter == 'Scott Halpern')  or (speaker.Presenter == 'Victoria Barone') or (speaker.Presenter == 'Maxwell Chomas') or (speaker.Presenter == 'Nancy Rigotti') or (speaker.Presenter == 'Shaoying Ma') or (speaker.Presenter == 'Charles Courtemanche') or (speaker.Presenter == 'Revathy Suryanarayana') or (speaker.Presenter == 'Kevin Callison') or (speaker.Presenter == 'Megan Piper') or (speaker.Presenter == 'Alex Liber') or (speaker.Presenter == 'Theodore Wagener') or (speaker.Presenter == 'Christian Saenz') or (speaker.Presenter == 'Brendan Cirillo') or (speaker.Presenter == 'Yichen Fang') or (speaker.Title == 'Electronic cigarettes and subsequent cigarette smoking in young people: methodological considerations and results from a Cochrane Review') or (speaker.Presenter == 'Sooa Ahn') or (speaker.Presenter == 'Samuel Sturm') or (speaker.Presenter == 'Annika Theodoulou') or (speaker.Presenter == 'Guillermo Paraje') or (speaker.Presenter == 'Jerome Adda') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a></td>
</tr>
{% elsif (speaker.Presenter == 'Hunt Allcott') or (speaker.Presenter == 'Justin White') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a></td>
</tr>
{% elsif (speaker.Presenter == '(1) Arjun Teotia / (2) Daphne Wu') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides #1</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}">Slides #2</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper #1</a></td>
</tr>
{% elsif (speaker.Presenter == 'Nancy Rigotti ') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper #1</a>|<a href="{{ speaker.PublishedPaper}}"> Paper #2</a></td>
</tr>
{% elsif (speaker.Presenter == 'Peter Hajek') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.PublishedPaper }}">Published Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'Alex Liber') or (speaker.Presenter == 'Andrew Barnes') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper #1</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}"> Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}"> Paper #3</a></td>
</tr>
{% elsif (speaker.Presenter == 'Andrea Villanti') or (speaker.Presenter == 'Rachel Cassidy') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper #1</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}"> Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}"> Paper #3</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}"> Paper #4</a></td>
</tr>
{% elsif (speaker.Presenter == 'Lucy Popova') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper #1</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}"> Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}"> Paper #3</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}"> Paper #4</a>|<a href="{{ speaker.ReadingList }}" download="{{ speaker.ReadingList }}"> Paper #5</a>|<a href="{{ speaker.MorePaper }}" download="{{ speaker.MorePaper }}"> Paper #6</a></td>
</tr>
{% elsif (speaker.Presenter == 'Anne Burton') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Working Paper</a></td>
</tr>
{% elsif speaker.Presenter == 'Kym Sterling' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Partial Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a></td> 
</tr>
{% elsif speaker.Presenter == 'Neal Benowitz, Joanna Cohen, Michael Cummings' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.ReadingList }}">Reading List</a></td> 
</tr>
{% elsif speaker.Presenter == 'Lisa Cox' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper </a>|<a href="{{ speaker.ReadingList }}">Reading List</a></td> 
</tr>
{% elsif speaker.Presenter == 'Susan Athey, Miguel Hernan, Elizabeth Stuart' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a> </td>
</tr>
{% elsif speaker.Presenter == 'Paul Rodriguez-Lesmes' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Working Paper #1</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}">Working Paper #2</a>|<a href="{{ speaker.PublishedPaper}}" download="{{ speaker.PublishedPaper }}">Published Paper (January 2023)</a>|<a href="{{ speaker.MorePaper}}" download="{{ speaker.MorePaper}}">Published Paper (August 2024)</a> </td> 
</tr>
{% elsif speaker.Presenter == 'John Buckell' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (January 2022)</a></td>
</tr>
{% elsif speaker.Presenter == 'Ce Shang' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (July 2022)</a></td>
</tr>
{% elsif speaker.Presenter == 'Ernest Dorilas' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (March 2022)</a></td>
</tr>
{% elsif speaker.Presenter == 'Joseph Sabia' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (December 2023)</a></td>
</tr>
{% elsif speaker.Presenter == 'Robert West' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft}}" download="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (March 2022)</a></td>
</tr>
{% elsif speaker.Presenter == 'Julia Dennett' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (May 2023)</a></td>  
</tr>  
 {% elsif speaker.Presenter == 'Reto Auer' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Published Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (open access)</a></td>  
</tr>  

   {% elsif speaker.Presenter == 'Jim Thrasher' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Paper #1</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}">Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}">Paper #3</a>|<a href="{{ speaker.ReadingList }}" download="{{ speaker.ReadingList }}">Referenced Studies</a></td>  

</tr> 
   {% elsif (speaker.Presenter == 'Hojin Park ') %}
<tr>
 <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Transcript }}" download="{{ speaker.Transcript }}">Transcript</a></td>
</tr>


   {% elsif (speaker.Presenter == 'Doug Levy') %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links (Other materials are embargoed until a later date): <a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a></td>  
</tr>
{% elsif (speaker.Presenter == 'Travis Whitacre') or (speaker.Presenter == 'Colin Reinhardt') or (speaker.Presenter == 'Caitlin Notley') or (speaker.Presenter == 'Erfan Loghmani') or (speaker.Presenter == 'Dana Mowls Carroll') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a>|<a href="{{ speaker.Transcript }}" download="{{ speaker.Transcript }}">Transcript</a></td>
</tr>


   {% elsif speaker.Presenter == 'Benjamin Toll' %}
<tr>
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Paper #1</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}">Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}">Paper #3</a>|<a href="{{ speaker.ReadingList }}" download="{{ speaker.ReadingList }}">Paper #4</a>|<a href="{{ speaker.PublishedPaper}}" download="{{ speaker.PublishedPaper }}">Paper #5</a>|<a href="{{ speaker.Transcript}}" download="{{ speaker.Transcript}}">Transcript</a>  </td>  

</tr> 
{% else %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a></td>
</tr>
{% endif %}


<tr style="border-bottom:1px solid black">
  <td colspan="100%"></td>
</tr>

 {% endfor %}
