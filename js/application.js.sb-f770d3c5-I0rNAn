{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf500
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 'use strict';\
 \
(function () \{\
  $(document).ready(function () \{\
    // Initialises Tableau Data Extension\
    tableau.extensions.initializeAsync().then(function () \{\
        refresh();\
    \}, function () \{ console.log('Error while Initializing: ' + err.toString()); \});\
  \});\
 \
  function refresh() \{\
    // Gets a list of the worksheets and adds them to the web page.\
    $("#worksheets").text("");\
    tableau.extensions.dashboardContent.dashboard.worksheets.forEach(function (worksheet) \{\
        $("#worksheets").append("<button class='btn btn-secondary btn-block'>"+worksheet.name+"</button>");\
    \});\
  \}\
\})();}