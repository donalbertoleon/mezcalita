---
layout: page
title: "Ejercicio 1"
---
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

1. ¿Es verdadera o falsa la siguiente expresión?


$$ \theta \lim_{x \to o}\left \{ \sum  \right \}\frac{ac}{bd} $$


{% assign q1-text = "¿Es correcta la expresión?" %}
{% assign q1-choices = "Verdadero, Falso" | split: ', ' %}
{% assign q1_feedbacks = "¡Correcto!  Excelente trabajo., Error. Inténtalo nuevamente." | split: ', ' %}
{% assign q1-correct = 0 %}
{% include mc-quiz.html text=q1-text choices=q1-choices answer=q1-correct feedback=q1_feedbacks %}


2. Bli-bli-bli


$$ \theta \lim_{x \to o}\left \{ \sum  \right \}\frac{ac}{bd} $$


{% assign q1-text = "¿Es correcta la expresión?" %}
{% assign q1-choices = "Verdadero, Falso" | split: ', ' %}
{% assign q1_feedbacks = "Error. Inténtalo nuevamente., ¡Correcto!  Excelente trabajo." | split: ', ' %}
{% assign q1-correct = 1 %}
{% include mc-quiz.html text=q1-text choices=q1-choices answer=q1-correct feedback=q1_feedbacks %}
