---
layout: page
title: About Kyle
header : 
group: navigation
weight : 5
---
{% include JB/setup %}

<div class="header">
	<img src="{{ ASSET_PATH }}twitter/images/kyle-ledbetter.jpg" class="avatar img-circle hidden-phone" />
	<div class="well well-small">
		<div class="row-fluid clearfix">
			<div class="span8">
				<ul class="list-unstyled">
					<li><strong>Principal User Experience Designer</strong></li>
					<li>MetaScale (Sears Brands LLC.) </li>
				</ul>
			</div>
			<div class="span4">
				<ul class="list-unstyled">
					<li><strong>Austin, Texas</strong></li>
					<li>originally from Baton Rouge, LA</li>
				</ul>
			</div>
		</div>
	</div>
	<div class="well well-small">
		<div class="row-fluid clearfix">
			<div class="span4">
				<div class="progress">
					<div class="progress-bar progress-bar-success" style="width:95%">UX/UI Design</div>
				</div>
				<div class="progress">
					<div class="progress-bar progress-bar-primary" style="width:85%">HTML5/CSS3/LESS/Bootstrap</div>
				</div>
				<div class="progress">
					<div class="progress-bar progress-bar-info" style="width:75%">Joomla 3.0 UX</div>
				</div>
				<div class="progress">
					<div class="progress-bar progress-bar-warning" style="width:85%">Adobe Creative Suite</div>
				</div>
				<ul class="list-unstyled">
					<li>UX/UI Design</li>
					<li></li>
					<li>Joomla User Experience</li>
					<li>Adobe Creative Suite (FW)</li>
				</ul>
			</div>
			<div class="span4">
				<ul class="list-inline list-labels">
					<li><span class="label label-info">osx</span></li>
					<li><span class="label label-success">css</span></li>
					<li><span class="label label-info">less</span></li>
					<li><span class="label label-primary">html5</span></li>
					<li><span class="label label-success">fireworks</span></li>
					<li><span class="label label-primary">responsive</span></li>
					<li><span class="label label-primary">ux</span></li>
					<li><span class="label label-success">ui</span></li>
					<li><span class="label label-success">joomla</span></li>
					<li class="hidden-tablet"><span class="label label-info">iphone</span></li>
					<li class="hidden-tablet"><span class="label label-info">ipad</span></li>
					<li class="hidden-tablet"><span class="label label-info">retina</span></li>
					<li class="hidden-tablet"><span class="label label-warning">jquery</span></li>
				</ul>
			</div>
		</div>
	</div>
</div>
<div class="row-fluid">
	<div class="span6">
		<h3 class="page-header">Recent Activity</h3>
		<ul class="posts list-unstyled">
		  {% for post in site.posts %}
		    <li><span class="muted pull-right">{{ post.date | date_to_string }}</span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><hr /></li>
		  {% endfor %}
		</ul>
	</div>
	<div class="span6">
		<h3 class="page-header">Recent Dribbble Shots</h3>
		<ul id="shotsByPlayerId" class="shotList list-inline"></ul>
	</div>
</div>
