---
title: Form | Forsta
layout: base.njk
---

<nav aria-label="breadcrumb">
  <ol class="breadcrumbs">
    <li><a href="/">Home</a></li>
    <li><a href="/forms">Forms</a></li>
  </ol>
</nav>

# Form

A simple form example

<form>
  <label>
    First Name
    <input type="text" id="first_name" />
  </label>
  <label>
    Last Name
    <input type="text" id="last_name" />
  </label>
  <label>
    Gender
    <select id="gender">
      <option value="male">Male</option>
      <option value="female">Female</option>
    </select>
  </label>
  <label>
    Bio
    <textarea id="bio" rows="6"></textarea>
  </label>
  <label class="checkbox">
    <input type="checkbox" id="newsletter" />
    <span>Sign up to receive news</span>
  </label>
  <div>
    <button type="submit">Sign Up</button>
  </div>
</form>
