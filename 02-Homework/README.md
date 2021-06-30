# 01 HTML, CSS, and Git: Code Refactor for Coding Bootcamp

## Introduction

This project required the refactoring of existing code to make it accessibility-friendly.

"**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers."

Below I will list the CSS and HTML changes from the project:

## Code Samples for both CSS and HTML

CSS:

		/*changed tag to header so that it's more accesibility friendly for those who need it*/
		header {
			padding: 20px;
			font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
			background-color: #2a607c;
			color: #ffffff;
		}

		/*combined class specificity below so that this looks more cleaned up and less tedious to look at*/

		#benefit-lead,
		#benefit-brand,
		#benefit-cost {
			margin-bottom: 32px;
			color: #ffffff;
		}

		#benefit-lead h3,
		#benefit-brand h3,
		#benefit-cost h3 {
			margin-bottom: 10px;
			text-align: center;
		}

		#benefit-lead img,
		#benefit-brand img,
		#benefit-cost img {
			display: block;
			margin: 10px auto;
			max-width: 150px;
		}

		#search-engine-optimization,
		#online-reputation-management,
		#social-media-marketing {
			margin-bottom: 20px;
			padding: 50px;
			height: 300px;
			font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
			background-color: #0072bb;
			color: #ffffff;
		}

		#search-engine-optimization img,
		#online-reputation-management img,
		#social-media-marketing img {
			max-height: 200px;
		}

		#search-engine-optimization h2,
		#online-reputation-management h2,
		#social-media-marketing h2 {
			margin-bottom: 20px;
			font-size: 36px;
		}

		/*changed tag to footer so that it's more accesibility friendly for those who need it*/

		footer {
			padding: 30px;
			clear: both;
			font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
			text-align: center;
		}

		/*changed h3 to h4 so that all the header attributes are sequential as asked for in the README.md*/

		footer h4 {
			font-size: 20px;
		}

HTML:
		<!--changed non-semantic tags to semantic for header and footer-->

		<body>
			<header>
				<h1>Hori<span class="seo">seo</span>n</h1>
				<nav>
					<ul>
						<li>
							<a href="#search-engine-optimization">Search Engine Optimization</a>
						</li>
						<li>
							<a href="#online-reputation-management">Online Reputation Management</a>
						</li>
						<li>
							<a href="#social-media-marketing">Social Media Marketing</a>
						</li>
					</ul>
				</nav>
			</header>

		<footer>
			<h4>Made with ❤️️ by Horiseon</h4>
			<p>
				&copy; 2019 Horiseon Social Solution Services, Inc.
			</p>
		</footer>

		<!--added semantic tag aside to class benefit-->
		<aside class="benefits"></aside>

		<!--changed last heading attribute from "h3" to "h4" so all headings are in sequential order-->
		<footer>
			<h4></h4>
		</footer>    

		<!--changed div to img for class=hero-->
		<img class="hero"></div>

		<!--added semantic tag section to class=content -->
    	<section class="content">

		<!--changed ":website" title to "How to Sustain and Grow your Business Online"-->
		 <title>How to Sustain and Grow your Business Online</title>

## Installation

- changed non-semantic tags to semantic for header and footer

- added semantic tag aside to class benefit

- changed last heading attribute from "h3" to "h4" so all headings are in sequential order

- changed class specificity to id to make #search-engine-optimization work properly and id for the other class values listed below
 
- combined below values

 "#benefit-lead h3,

 #benefit-brand h3,

 #benefit-cost h3"

  "#search-engine-optimization,
   
 #online-reputation-management,
  
 #social-media-marketing"
 
 as groups into one css selector for multiple selectors.

- changed div to img for class=hero

- added semantic tag section to class=content 

- changed ":website" title to "How to Sustain and Grow your Business Online"

## Screenshot of deployed website via IPhone

## Links to GitHub and deployed website

Link to website: https://kdassign.github.io/HW1/
Link to git hub repo: https://github.com/kdassign/HW1