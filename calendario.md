---
layout: page
title: Eventos
permalink: /calendar/
---

<script src="https://code.jquery.com/jquery-3.1.1.min.js"   
integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8="  crossorigin="anonymous"></script>
<script type="text/javascript" src="/script/moment.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.2.0/fullcalendar.min.js"></script>
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.2.0/fullcalendar.min.css">
<link rel="stylesheet" media="print" href="//cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.2.0/fullcalendar.print.css">

<script>
$(document).ready(function() {

	$('#calendar').fullCalendar({
		events:'/calendar-data'
	})

});

</script>


{% for evento in site.eventos %}
{{evento.title}} {{evento.fecha}}<br/>
{% endfor %}

<div id="calendar"></div>
