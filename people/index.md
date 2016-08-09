---
layout: page
title: People
---
<script language="javascript">

	function nospam(id, domain) {
	    var at = "@";
	    if(domain.localeCompare("iisc") == 0)
	    	domain = "csa.iisc.ernet.in";
	    return id + at + domain;
	}

	function writeid(id, domain) {
	    document.write("<a href=\"mailto:" + nospam(id, domain) +"\">" + nospam(id, domain) + "</a>");
}
</script>


***

## Convenor
* [K. Gopinath (कांचि गोपीनाथ)](http://drona.csa.iisc.ernet.in/~gopi/){:target="_blank"}<br>
<script language='javascript'>writeid('gopi', 'iisc');</script><br>
<p class="message">
K. Gopinath is a professor at Indian Institute of Science in the Computer Science and Automation Department.<br><br>
His education has been at IIT-Madras (B.Tech'77), University of Wisconsin, Madison (MS'80) and Stanford University (PhD'88). 
He has also worked at AMD (Sunnyvale) ('80-'82), and as a PostDoc ('88-'89) at Stanford, and also briefly at Sun Microsystems Labs ('90).<br><br>
His research interests are primarily in the computer systems area (Operating Systems, Storage Systems, Systems Security and Systems Verification).
</p>

***

## Current Students

### Ph.D.

<table>
{% for member in site.data.phd %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>


### M.Tech (Research) / M.Sc. Engg

<table>
{% for member in site.data.mtech_res %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>


### M.Tech / M.E.

* [Alumni](alumni)

<table>
{% for member in site.data.me %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>


### Research Assistant

<table>
{% for member in site.data.ra %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>


### Project Staff

<table>
{% for member in site.data.project %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>


<!-- ### Intern

<table>
{% for member in site.data.intern %}
 	<tr >
 		<td>
	 		&#8226;
	 	</td>
	 	<td>
	 		<img src='{{ site.url }}/images/{{ member.image }}' width='90' height='100' border='1' />
	 	</td>
	 	<td>
		 	<a href="{{ member.homepage }}" target="_blank"><b>{{ member.name }}</b></a><br>
		 	<script language='javascript'>writeid('{{ member.id }}', '{{ member.domain }}');</script><br>
		 	Research Area: {{ member.research }}
	 	</td>
	 </tr>
{% endfor %}
</table>
 -->
 
### Alumni
<table>
	<td>
	 	&#8226;
	 </td>
	 <td>
	 	<a href="alumni/"><b>View</b></a>
	 </td>
</table>


***
***
