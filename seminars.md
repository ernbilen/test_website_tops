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
{% elsif (speaker.Presenter == 'Michael Darden') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (March 2021)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Kai-Wen Cheng') %}
<tr>
  <td id="kai" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2022)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Christopher Carpenter') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (August 2021)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Catherine Maclean') %}
<tr id="jcm">
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (September 2022)</a></td>
</tr>
{% elsif (speaker.Presenter == 'Jamie Hartmann-Boyce') or (speaker.Presenter == 'Aryn Phillips') or (speaker.Presenter == 'Jon Oliver') or (speaker.Presenter == 'Hai Nguyen') or (speaker.Presenter == 'Marcus Munafo') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'Robert West') or (speaker.Presenter == 'Abigail S. Friedman')  or (speaker.Presenter == 'Rizki Siregar') or (speaker.Presenter == 'Dan Sacks') or (speaker.Presenter == 'Lauren Hoehn-Velasco') or (speaker.Presenter == 'Ying Yao') or (speaker.Presenter == 'Rachana Bhatt') or (speaker.Presenter == 'Dhaval Dave') or (speaker.Presenter == 'Katherine Meckel') or (speaker.Presenter == 'Aisha Baisalova') %}
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

{% elsif (speaker.Presenter == 'Scott Halpern') or (speaker.Presenter == 'Ce Shang') or (speaker.Presenter == 'Ernest Dorilas')  or (speaker.Presenter == 'Victoria Barone') or (speaker.Presenter == 'Joseph Sabia') or (speaker.Presenter == 'Maxwell Chomas') or (speaker.Presenter == 'Julia Dennett') or (speaker.Presenter == 'Nancy Rigotti') or (speaker.Presenter == 'Erica Mtenga') or (speaker.Presenter == 'Shaoying Ma') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a></td>
</tr>
{% elsif (speaker.Presenter == 'Hunt Allcott') or (speaker.Presenter == 'Rahi Abouk') or (speaker.Presenter == 'Justin White') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper</a></td>
</tr>
{% elsif (speaker.Presenter == '(1) Arjun Teotia / (2) Daphne Wu') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides #1</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}">Slides #2</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}">Working Paper #1</a></td>
</tr>
{% elsif (speaker.Presenter == 'Peter Hajek') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.PublishedPaper }}">Published Paper</a></td>
</tr>
{% elsif (speaker.Presenter == 'Alex Liber') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}"> Paper #1</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}"> Paper #2</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}"> Paper #3</a></td>
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
{% elsif speaker.Presenter == 'Susan Athey, Miguel Hernan, Elizabeth Stuart' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a></td>
</tr>
{% elsif speaker.Presenter == 'Paul Rodriguez-Lesmes' %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">Q&A</a>|<a href="{{ speaker.Draft }}" download="{{ speaker.Draft }}">Working Paper #1</a>|<a href="{{ speaker.Draft2 }}" download="{{ speaker.Draft2 }}">Working Paper #2</a></td>
</tr>
{% elsif speaker.Presenter == 'John Buckell' %}
  <td id="anchor1" colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a>|<a href="{{ speaker.PublishedPaper }}" download="{{ speaker.PublishedPaper }}">Published Paper (January 2022)</a></td>
{% else %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a></td>
</tr>
{% endif %}


<tr style="border-bottom:1px solid black">
  <td colspan="100%"></td>
</tr>

 {% endfor %}
