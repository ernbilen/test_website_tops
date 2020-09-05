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
  <td colspan="2" height="40" valign="top" class="registration"><a href="{{ speaker.Video }}">Video</a>,<a href="{{ speaker.Paper }}">Slides</a></td>
</tr>
<tr>
  <td width="150" valign="top" class="time">{{ speaker.Time }}</td>
   <td height="30" valign="top" class="paper">"{{ speaker.Title }}"</a></td>
</tr>

<tr style="border-bottom:1px solid black">
  <td colspan="100%"></td>
</tr>

 {% endfor %}
</table>
