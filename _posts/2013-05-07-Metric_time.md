---
title: Metric time
main_file: metric_time.py
status: no update planned
layout: addon
permalink: Metric_time.html
status_color: red
status_text_color: white
abstract: Shows times in some spots as days or years.
first_image: Studied%20in%20days.png
first_alt: The time studied is shown in days, not hours.
first_caption: 5.6 centidays
---
This add-on is just me riding my favorite hobby horse,
[metric time](http://en.wikipedia.org/wiki/Decimal_time#Fractional_days).
I think splitting days into hours, minutes and seconds is about as
silly as splitting lengths into inches, feet, yards, rods, chains and
miles or using pounds and ounces and stones and who-knows-what else for
mass. (Or weight. Better not go
[there](http://en.wikipedia.org/wiki/Slug_(mass))! And how much is a
[gallon](http://en.wikipedia.org/wiki/Gallon)‽)

<blockquote class="nb">
This add-on needs extra Python packages. See the
<q><a href="Batteries.html">Batteries</a></q> page for details.
</blockquote>

This add-on replaces the standard time-formatting function with one
that returns times shorter than a year as days – even times much
shorter than a day. Longer times are written as years with one decimal
place.

<blockquote class="nb">This is an Anki 2.0 plugin. I have no plans of
updating it. People that are interrested in this are welcome to take
this over.</blockquote>

## AnkiDroid

Daring spirits can use my
[branch](https://github.com/ospalh/Anki-Android/tree/feature-metric-time)
of AnkiDroid
[development branch](https://github.com/ankidroid/Anki-Android/tree/v2.1-dev).

I have added the equivalent of this add-on, showing times as fractional
days in AnkiDroid. You should merge this branch into the newest
version of AnkiDroid, not just use that branch as-is. I forked this off
the the 2.1 branch. Merging it into the 2.0 branch may or
may not work.
