---
layout: page
title: Expenses-OCR
description: "<b>Mobile App using OCR to process invoces</b> | BSc project | 2018/2019 | Supervisor" 
img: /assets/img/expensesOCR_cover.jpg
categories: academic
importance: 4
---

The problem was introduced by an external company as a challenge (Softinsa/IBM) and independently supervised by me at IPT and developed by <a href="https://github.com/helderfoca" target="_blank">Hélder Lopes</a> and <a href="https://github.com/aluno19987" target="_blank">Edgar Oliveira</a>: a solution to improve how collaborators report travel expenses. The students developed an Android application (prototype), which uses optical characters recognition and machine learning, to scan invoices (e.g., meal, gas, train) and recognize the type and expense, introducing it in the system.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR_diagram.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR7.jpg' | relative_url }}" alt="" title="Processed invoice"/>
    </div>
</div>
<div class="caption">
    ExpensesOCR sequence diagram (in PT, from the BSc project report), and an invoice processed with OpenCV.
</div>

To this end, the students were tested several different solutions, settling with Android native development, OpenCV for OCR and MonkeyLearn to the the text classification into one of the possible categories.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR1.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR3.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR4.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
</div>
<div class="caption">
    Aplication screenshots for login, scanning the photo of an invoice and auto-filling the forms.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR2.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR5.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/expensesOCR6.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
</div>
<div class="caption">
    Application capturing an invoice and detecting the invoice edges.
</div>
