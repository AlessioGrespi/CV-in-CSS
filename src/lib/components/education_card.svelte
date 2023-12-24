<div class="flex w-full justify-between mx-0.5 my-1 bg-slate-200 rounded py-1">
	<div class="flex justify-center w-24">
		<slot name="logo" />
	</div>
	<div class="flex flex-col w-11/12">
		<h4 class="text-slate-400"><slot name="university" /></h4>
		<div class="flex">
			<h3><slot name="course" /></h3>
			<h4 class="pl-1 font-semibold text-slate-400 self-center tracking-tighter">
				<slot name="dates" />
			</h4>
		</div>
		<div class="flex italic">
			<p><span class="font-semibold">Grade: </span><slot name="grade" /></p>
		</div>
        <div class="flex">
			<p><span class="font-semibold">Relevant Modules: </span><slot name="modules" /></p>
		</div>
	</div>
</div>
