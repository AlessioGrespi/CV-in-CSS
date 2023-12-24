<script>
	import ContactPill from '$lib/components/contact_pill.svelte';
import CvHeader from '$lib/components/cv_header.svelte';
	import CvSection from '$lib/components/cv_section.svelte';
	import EducationCard from '$lib/components/education_card.svelte';
	import JobCard from '$lib/components/job_card.svelte';
	import LanguageSpoken from '$lib/components/language_spoken.svelte';
	import SkillsPill from '$lib/components/skills_pill.svelte';
</script>

<CvHeader>
	<div>
		<h1 class="font-semibold">Alessio Grespi</h1>
		<h2>MSc Aerial Robotics, University of Bristol</h2>
		<!-- <h3>BEng Robotics, Mechatronics and Control Engineering, Loughborough University</h3> -->
	</div>
	<div>
        <ContactPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/phone.svg" />
            <p>+44 7490 880680</p>
        </ContactPill>
        <ContactPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/email.svg" />
            <p>alessiogrespi@gmail.com</p>
        </ContactPill>
        <ContactPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/linkedin.svg" />
            <p>https://www.linkedin.com/in/alessio-grespi/</p>
        </ContactPill>
        <ContactPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/github.svg" />
            <p>https://github.com/AlessioGrespi</p>
        </ContactPill>
	</div>
</CvHeader>

<CvSection>
	<h2 class='bg-slate-200 rounded m-0.5 w-full px-2 pb-0.5'>Work Experience</h2>
	<div>
		<JobCard>
			<span slot="logo"
				><img
					class="max-w-16 max-h-20"
					alt="logo"
					src="src\lib\images\LSU.png"
				/></span
			>
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
		<JobCard>
			<span slot="logo"
				><img
					class="justify-self-center pt-5 max-w-16"
					alt="logo"
					src="src\lib\images\amazon-logo.png"
				/></span
			>
			<span slot="job-position">Technical Program Manager</span>
			<span slot="company">Amazon Robotics</span>
			<span slot="job-dates">- Jan 2021 - Jul 2021</span>
			<!-- <span slot="job-summary"
                >My Primary role was to generate ideas for events and activities in LSU Enterprise as well
                as hosting them</span
            > -->
			<span slot="job-bullets"
				><li>
					Evaluated project management tools for team and internal customers use, this involved
					reaching out to stakeholders for building out customer profiles and requirements matrices.
				</li>
				<li>
					Created a Tableau dashboard with the aid of SQL which covered the fundamental metrics for
					Fulfilment Centres (FCs) across the EU and North America regions, providing an overview
					from a network level all the way down to a zone-by-zone basis within each FC. This allowed
					for later data analysis for FC optimisation.
				</li>
				<li>
					Developed and expanded on documentation for a new storage system for Amazon Fulfilment
					Centres (FCs).
				</li></span
			>
		</JobCard>
		<JobCard>
			<span slot="logo"
				><img
					class="justify-self-center pt-5 max-w-16"
					alt="logo"
					src="src\lib\images\crest-purple.png"
				/></span
			>
			<span slot="job-position">Placement Year in Enterprise</span>
			<span slot="company">Loughborough University</span>
			<span slot="job-dates">- Jul 2020 - Aug 2021</span>
			<!-- <span slot="job-summary"
                >My Primary role was to generate ideas for events and activities in LSU Enterprise as well
                as hosting them</span
            > -->
			<span slot="job-bullets"
				><li>
					Wrote a business plan and documentation for a SaaS based, hiring software, which I am now
					developing.
				</li>
				<li>
					Attended various workshops on business development and management/administration. This
					included market research, accounting, and the business model canvas as well as business
					pitching.
				</li>
				<li>
					Attended a virtual summer camp where we had to develop a business idea from scratch over
					the course of 6 weeks. At the end we presented to a panel of Angel Investors who praised
					us for our idea and product pitch.
				</li></span
			>
		</JobCard>
	</div>
</CvSection>

<CvSection>
	<h2 class='bg-slate-200 rounded m-0.5 w-full px-2 pb-0.5'>Education</h2>
	<EducationCard>
		<span slot="logo"
			><img
				class="justify-self-center max-w-16 pt-1 max-h-20"
				alt="logo"
				src="src\lib\images\bristol.png"
			/></span
		>
		<span slot="university">University of Bristol</span>
		<span slot="course">MSc Aerial Robotics</span>
		<span slot="dates">- Sep 2022 - Dec 2023</span>
		<span slot="modules"
			>Robotics Research Technology and Methods, Introduction to Artificial Intelligence, Disaster
			Resilience and Sustainable Development.</span
		>
		<span slot="grade">On track for a Merit</span>
	</EducationCard>
	<EducationCard>
		<span slot="logo"
			><img
				class="justify-self-center max-w-16 max-h-20"
				alt="logo"
				src="src\lib\images\crest-purple.png"
			/></span
		>
		<span slot="university">Loughborough University</span>
		<span slot="course">BEng Robotics, Mechatronics and Control Engineering</span>
		<span slot="dates">- Oct 2018 - Jul 2022</span>
		<span slot="grade"
			>Second Class: Upper Division with Honours (2:1, Hons), and a Diploma of Professional Studies
			(DPS)</span
		>
		<span slot="modules"
			>Systems Engineering Applications, Introduction to Programming, Engineering Management:
			Finance, Law and Quality, Engineering Project Management</span
		>
	</EducationCard>
</CvSection>
<!-- 
<CvSection>
	<h2>Skills</h2>
	<div class="flex items-center">
		<h3>Languages:</h3>
		<LanguageSpoken>
			<span slot="emoji">🇬🇧 </span>
			<span slot="language">English</span>
			<span slot="level">(Native)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇮🇹 </span>
			<span slot="language">Italian</span>
			<span slot="level">(Advanced)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇪🇸 </span>
			<span slot="language">Spanish</span>
			<span slot="level">(Advanced)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇷🇺 </span>
			<span slot="language">Russian</span>
			<span slot="level">(Basic)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇫🇷 </span>
			<span slot="language">French</span>
			<span slot="level">(Basic)</span>
		</LanguageSpoken>
	</div>
	<div class="flex items-center">
		<h3>Programming Languages:</h3>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/python.svg" />
			<h3>Python</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/html.svg" />
			<h3>HTML</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/css.svg" />
			<h3>CSS</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/SQL.svg" />
			<h3>SQL</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/MATLAB.svg" />
			<h3>MATLAB</h3>
		</SkillsPill>
	</div>

	<div class="flex items-center">
		<h3>Software:</h3>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Tableau.svg" />
			<h3>Tableau</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/vscode.svg" />
			<h3>Visual Studio Code</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/excel.svg" />
			<h3>Excel</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/GitHub.svg" />
			<h3>GitHub</h3>
		</SkillsPill>
	</div>

	<div class="flex items-center">
		<h3>Technologies and Frameworks:</h3>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/SvelteKit.svg" />
			<h3>SvelteKit Front-End Framework</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/sass.svg" />
			<h3>Sass</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Tailwind.svg" />
			<h3>Tailwind CSS</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Prisma.svg" />
			<h3>Prisma ORM</h3>
		</SkillsPill>
	</div>
</CvSection> -->


<CvSection>
	<div class="flex justify-center">
		<LanguageSpoken>
			<span slot="emoji">🇬🇧 </span>
			<span slot="language">English</span>
			<span slot="level">(Native)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇮🇹 </span>
			<span slot="language">Italian</span>
			<span slot="level">(Advanced)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇪🇸 </span>
			<span slot="language">Spanish</span>
			<span slot="level">(Advanced)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇷🇺 </span>
			<span slot="language">Russian</span>
			<span slot="level">(Basic)</span>
		</LanguageSpoken>
		<LanguageSpoken>
			<span slot="emoji">🇫🇷 </span>
			<span slot="language">French</span>
			<span slot="level">(Basic)</span>
		</LanguageSpoken>
	</div>
	<div class="flex justify-center flex-wrap">
		<!-- <h3>Skills: </h3> -->
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/python.svg" />
			<h3>Python</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/html.svg" />
			<h3>HTML</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/css.svg" />
			<h3>CSS</h3>
		</SkillsPill>
        <SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/JavaScript.svg" />
			<h3>JavaScript</h3>
		</SkillsPill>
        <SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/TypeScript.svg" />
			<h3>TypeScript</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/SQL.svg" />
			<h3>SQL</h3>
		</SkillsPill>
		<SkillsPill>
			<img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/MATLAB.svg" />
			<h3>MATLAB</h3>
		</SkillsPill>
	</div>
    <div class="flex justify-center flex-wrap">
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/SvelteKit.svg" />
            <h3>SvelteKit Front-End Framework</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/sass.svg" />
            <h3>Sass</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Tailwind.svg" />
            <h3>Tailwind CSS</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Prisma.svg" />
            <h3>Prisma ORM</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/matplotlib.png" />
            <h3>Matplotlib</h3>
        </SkillsPill>

    </div>

    <div class="flex justify-center flex-wrap">
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/Tableau.svg" />
            <h3>Tableau</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/vscode.svg" />
            <h3>Visual Studio Code</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/excel.svg" />
            <h3>Excel</h3>
        </SkillsPill>
        <SkillsPill>
            <img class="h-3.5 self-center mr-1" alt="ass" src="src/lib/images/GitHub.svg" />
            <h3>GitHub</h3>
        </SkillsPill>
    </div>
</CvSection>