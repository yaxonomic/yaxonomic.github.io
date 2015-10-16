---
layout: page
title: Requirements
permalink: /requirements/
rel: ..
---
Functional Requirements
<ul>
	<li>Map genetic reads to references at in the NCIB database in order to identify the organisms within the sample.</li>
	<li>Provide information on the level of certainty for an identification.</li>
	<li>Pipeline must track its current step in the process.</li>
	<li>Must be able to recover from a failure and restart where it left off.</li>
	<li>Must meet certain benchmarks for the indentification of different species as well as for the level of precision.</li>
</ul>

Non-functional Requirements:
<ul>
	<li>Fast.</li>
	<li>Modular. Different modules of the pipeline must be able to be swapped out.</li>
	<li>Well documented and easy to modify.</li>
</ul>
