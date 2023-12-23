<div class="flex w-full justify-between">
	<div class="w-1/6 flex justify-center">
		<slot name='logo'/>
	</div>
	<div class="flex flex-col w-5/6">
		<h4 class="text-slate-400"><slot name="job-position" /></h4>
		<div class="flex">
			<h3><slot name="company" /></h3>
			<h4 class="pl-1 font-semibold text-slate-300 self-center tracking-tighter">
				<slot name="job-dates" />
			</h4>
		</div>
		<p>
			<slot name="job-summary" />
		</p>
		<ul class="list-disc ml-4">
			<slot name="job-bullets" />
		</ul>
	</div>
</div>
