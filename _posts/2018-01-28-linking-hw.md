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
    output, input, span {
      display:inline-block;
    }
    .box {
      border: 1 px #999;
      width: 100%;
    }
    /* OUTPUT AREA */
    #exampleSite1{

    }
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
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script type="text/javascript" charset="utf-8">
      jQuery(function($) {

      var copyCommandSupported = document.queryCommandSupported('copy');
      $('#featureDetectMsg').text('Copy command supported: ' + copyCommandSupported);

      $('#copyButton').click(function() {
        var preElement = $('#exampleSite1')[0];
        copyToClipboard(preElement, showSuccessMsg);
      });

      function showSuccessMsg() {
        $('#successMsg').finish().fadeIn(30).fadeOut(1000);
      }

      function copyToClipboard(element, successCallback) {
        selectText(element);

        var succeeded;
        try {
          succeeded = document.execCommand('copy');
        } catch (e) {
          succeeded = false;
        }

        if (succeeded && typeof(successCallback) === 'function') {
          successCallback();
        }

        deselect(element);
      }

      function selectText(element) {
        if (/INPUT|TEXTAREA/i.test(element.tagName)) {
          element.focus();
          if (element.setSelectionRange) {
            element.setSelectionRange(0, element.value.length);
          } else {
            element.select();
          }
          return;
        }

        var rangeObj, selection;
        if (document.createRange) { // IE 9+ and all other browsers
          rangeObj = document.createRange();
          rangeObj.selectNodeContents(element);
          selection = window.getSelection();
          selection.removeAllRanges();
          selection.addRange(rangeObj);
        } else if (document.body.createTextRange) { // IE <=8
          rangeObj = document.body.createTextRange();
          rangeObj.moveToElementText(element);
          rangeObj.select();
        }
      }

      function deselect(element) {
        if (element && /INPUT|TEXTAREA/i.test(element.tagName)) {
          if ('selectionStart' in element) {
            element.selectionEnd = element.selectionStart;
          }
          element.blur();
        }

        if (window.getSelection) { // IE 9+ and all other browsers
          window.getSelection().removeAllRanges();
        } else if (document.selection) { // IE <=8
          document.selection.empty();
        }
      }

    });
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
              <span id="exampleSite1" style="display: inline-block !important; width: auto;">
              https://github.com/<output type="text" class="username" name="some_name" value="" id="Siteurl" onkeyup="updateSiteurl();"></output>/
              </span>
              <span>
                <button type="button" id="copyButton">Copy</button>
                <span id="successMsg" style="display:none;">Copied!</span>
              </span>
            </p>

            <p class="sites">
              Your assignment's <b>repo</b> is&nbsp;&nbsp;&nbsp;
              <span id="exampleSite2" style="display: inline-block !important; width: auto;">
              https://github.com/<output type="text" class="username" name="some_name" value="" id="Siteurl2" onkeyup="updateSiteurl();"></output>/web-dev-hw/tree/master/<output type="text" class="assignment" name="some_name" value="" id="Assignurl" onkeyup="updateAssignurl();"></output>/
              </span>
              <span>
                <button type="button" id="copyButton">Copy</button>
                <span id="successMsg" style="display:none;">Copied!</span>
              </span>
            </p>

            <p class="sites">
              Your assignment's <b>live site</b> is&nbsp;&nbsp;&nbsp;
              https://<output type="text" class="username" name="some_name" value="" id="Siteurl3" onkeyup="updateSiteurl();"></output>.github.io/web-dev-hw/<output type="text" class="assignment" name="some_name" value="" id="Assignurl2" onkeyup="updateAssignurl();"></output>/
              </span>
              <span>
                <button type="button" id="copyButton">Copy</button>
                <span id="successMsg" style="display:none;">Copied!</span>
              </span>
            </p>
          </div>
      </div>
    </div>
  </div>
</div>
