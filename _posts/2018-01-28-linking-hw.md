---
layout: post
title:  "FAQ: Linking Homework"
author: Justine
permalink: /posts/link-hw
---

<head>
  <style>
    /* INPUT AREA */
    p.sites {
      margin: 20px 0;
    }
    .username {
        color: #E95420 !important;
    }
    .assignment {
        color: #8BC34A !important;
    }
    output, input {
      display:inline-block !important;
    }

    /* OUTPUT AREA */


  </style>
  <!-- FORM -->
  <script type="text/javascript" charset="utf-8">
      function updateSiteurl(){
      username = document.getElementById("username").value;
      document.getElementById("Siteurl").value = username;
      document.getElementById("Siteurl2").value = username;
      document.getElementById("Siteurl3").value = username;
      document.getElementById("Siteurl4").value = username;
      }
      function updateAssignurl(){
      assignName = document.getElementById("assignName").value;
      document.getElementById("Assignurl").value = assignName;
      document.getElementById("Assignurl2").value = assignName;
      }
  </script>

  <!-- COPY BOX -->
  <script type="text/javascript" charset="utf-8">
  </script>
</head>


<img src="{{ site.url }}/img/ask-question.gif" title="How do I...?" alt="offering help by reaching through the computer screen" style="width: 100%; max-width: 250px; margin: auto;" />


<div class="row">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-danger">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-question-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Question:
          </h4>
        </div>
          <div class="panel-body">
            <h5 style="font-size: 18px;">"How do I link to my specific homework or assignment repository?"</h5>

            <p>
              My GitHub username is&nbsp;&nbsp;&nbsp;
              <span><input type="text" name="some_name" value="" id="username" onkeyup="updateSiteurl();"></span>&nbsp;,
            </p>

            <p>
              and I want to link to my&nbsp;&nbsp;&nbsp;
              <span><input type="text" name="some_name" value="" id="assignName" onkeyup="updateAssignurl();"></span>
              repo.
            </p>
          </div>
      </div>
    </div>
  </div>
</div>

<div class="row">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-success">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-exclamation-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Answer:
          </h4>
        </div>
          <div class="panel-body">
            <h5 style="font-size: 18px;">There are several links associated with GitHub:</h5>
            <p class="sites">
              Your profile is:&nbsp;&nbsp;&nbsp;
              https://github.com/<output type="text" class="username" name="some_name" value="" id="Siteurl" onkeyup="updateSiteurl();"></output>/
            </p>

            <p class="sites">
              Your assignment's <b>repo</b> is&nbsp;&nbsp;&nbsp;
              https://github.com/<output type="text" class="username" name="some_name" value="" id="Siteurl2" onkeyup="updateSiteurl();"></output>/web-dev-hw/tree/master/<output type="text" class="assignment" name="some_name" value="" id="Assignurl" onkeyup="updateAssignurl();"></output>/
            </p>

            <p class="sites">
              Your assignment's <b>live site</b> is&nbsp;&nbsp;&nbsp;
              https://<output type="text" class="username" name="some_name" value="" id="Siteurl3" onkeyup="updateSiteurl();"></output>.github.io/web-dev-hw/<output type="text" class="assignment" name="some_name" value="" id="Assignurl2" onkeyup="updateAssignurl();"></output>/
            </p>
          </div>
      </div>
    </div>
  </div>
</div>
