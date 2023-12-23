<script>
	import JobCard from '$lib/components/job_card.svelte';
</script>

<div class="flex justify-between border-b-4 pb-1">
	<div>
		<h1 class="font-semibold">Alessio Grespi</h1>
		<h2>MSc Aerial Robotics, University of Bristol</h2>
		<!-- <h3>BEng Robotics, Mechatronics and Control Engineering, Loughborough University</h3> -->
	</div>
	<div>
		<ul>
			<li>+44 7490 880680</li>
			<li>alessiogrespi@gmail.com</li>
			<li>https://www.linkedin.com/in/alessio-grespi/</li>
			<li>https://github.com/AlessioGrespi</li>
		</ul>
	</div>
</div>
<div>
	<h2>Work Experience</h2>
	<div>
		<JobCard>
            <span slot="logo"><img class="justify-self-center pt-4 max-h-20" alt="logo" src="src\lib\images\LSU.png"/></span>
			<span slot="job-position">Innovation Officer</span>
			<span slot="company">Loughborough Students' Union (Enterprise)</span>
			<span slot="job-dates">- Jun 2021 - Jun 2022</span>
			<span slot="job-summary"
				>My Primary role was to generate ideas for events and activities in LSU Enterprise as well
				as hosting them</span
			>
			<span slot="job-bullets"
				><li>
					Advised students on their business ideas, documents and pitches, and gave suggestions on
					what they could do to improve them
				</li>
				<li>
					Created and hosted my own event "Computer Science x LSU Enterprise Talent Match", to
					facilitate connections between student entrepreneurs and prospective developers. This
					event won Enterprise event of the year.
				</li></span
			>
		</JobCard>
		
	</div>
</div>
