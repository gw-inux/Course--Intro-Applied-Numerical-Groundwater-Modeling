---
title: Participant Survey
layout: home
nav_order: 3
parent: Introduction
has_children: false
---

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

# Participant Survey

## 1. Academic Level

What's your academic level (i.e., the latest academic certificate)?

<div>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Undergraduate student (BSc or equivalent)
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Undergraduate (BSc or equivalent)
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Graduate student (MSc or equivalent)
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Graduate (MSc or equivalent)
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> PhD Student
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> PhD
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Habilitation (or equivalent)
  </label>
  <br>
  <label>
    <input type="radio" name="academic-level" onclick="highlightOption(this)"> Other (please explain as a comment)
  </label>
</div>
<br>
Add a comment about the question: 
<textarea rows="3" cols="50"></textarea>

---

## 2. Field of Study

Please select the best fitting field of study, considering your research career:

<div>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Hydrogeology (earth sciences)
  </label>
  <br>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Hydrogeology (mine or civil engineering)
  </label>
  <br>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Geology
  </label>
  <br>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Water resources engineering
  </label>
  <br>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Agricultural sciences
  </label>
  <br>
  <label>
    <input type="radio" name="field-of-study" onclick="highlightOption(this)"> Others (add it as a comment)
  </label>
</div>
<br>
Add a comment about the question: 
<textarea rows="3" cols="50"></textarea>

---

## 3. How many years of technical experience do you have (excluding the overlapping period as a student)?

Just write a number (years): 
<input type="number" min="0" step="1">

---

## 4. What is your age in years?

Just write a number (years): 
<input type="number" min="0" step="1">

---

<script>
  function highlightOption(selectedOption) {
    // Reset all labels in the group
    const allOptions = selectedOption.closest('div').querySelectorAll('label');
    allOptions.forEach(option => option.style.color = 'black');

    // Highlight the selected label
    selectedOption.parentElement.style.color = 'blue';
  }
</script>





# Form:

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>
<form action="https://formspree.io/f/movqygpk" method="POST">
  <h2>1. Academic Level</h2>
  <p>What's your academic level (i.e., the latest academic certificate)?</p>
  <label><input type="radio" name="academic-level" value="Undergraduate student"> Undergraduate student (BSc or equivalent)</label><br>
  <label><input type="radio" name="academic-level" value="Undergraduate"> Undergraduate (BSc or equivalent)</label><br>
  <label><input type="radio" name="academic-level" value="Graduate student"> Graduate student (MSc or equivalent)</label><br>
  <label><input type="radio" name="academic-level" value="Graduate"> Graduate (MSc or equivalent)</label><br>
  <label><input type="radio" name="academic-level" value="PhD Student"> PhD Student</label><br>
  <label><input type="radio" name="academic-level" value="PhD"> PhD</label><br>
  <label><input type="radio" name="academic-level" value="Habilitation"> Habilitation (or equivalent)</label><br>
  <label><input type="radio" name="academic-level" value="Other"> Other</label><br>
  <textarea name="academic-comment" rows="3" cols="50" placeholder="Add a comment about the question"></textarea>

  <h2>2. Field of Study</h2>
  <p>Please select the best fitting field of study, considering your research career:</p>
  <label><input type="radio" name="field-of-study" value="Hydrogeology (earth sciences)"> Hydrogeology (earth sciences)</label><br>
  <label><input type="radio" name="field-of-study" value="Hydrogeology (mine or civil engineering)"> Hydrogeology (mine or civil engineering)</label><br>
  <label><input type="radio" name="field-of-study" value="Geology"> Geology</label><br>
  <label><input type="radio" name="field-of-study" value="Water resources engineering"> Water resources engineering</label><br>
  <label><input type="radio" name="field-of-study" value="Agricultural sciences"> Agricultural sciences</label><br>
  <label><input type="radio" name="field-of-study" value="Other"> Others</label><br>
  <textarea name="field-comment" rows="3" cols="50" placeholder="Add a comment about the question"></textarea>

  <h2>3. Years of Technical Experience</h2>
  <input type="number" name="experience-years" min="0" placeholder="Enter number of years"><br>

  <h2>4. Age</h2>
  <input type="number" name="age" min="0" placeholder="Enter your age"><br>

  <button type="submit">Submit</button>
</form>

