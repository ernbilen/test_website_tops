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
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Draft }}">Paper</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a></td>
</tr>

{% elsif (speaker.Presenter == 'Catherine Maclean')  or (speaker.Presenter == 'Hunt Allcott') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Draft }}">Paper</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides</a> |<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">QA</a></td>
</tr>
{% elsif  (speaker.Presenter == '(1) Arjun Teotia / (2) Daphne Wu') %}
<tr>
  <td colspan="2" height="40" valign="top" class="registration">Links: <a href="{{ speaker.Video }}">Video</a>|<a href="{{ speaker.Paper }}" download="{{ speaker.Paper }}">Slides #1</a>|<a href="{{ speaker.Paper2 }}" download="{{ speaker.Paper2 }}">Slides #2</a>|<a href="{{ speaker.Draft }}">Paper #1</a>|<a href="{{ speaker.QA }}" download="{{ speaker.QA }}">QA</a></td></td>
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
</table>
