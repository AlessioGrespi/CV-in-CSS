<script>
	import CvSection from "./cv_section.svelte";

</script>
<CvSection>
    <div class="flex justify-between border-b-4 mx-2">
        <slot/>
    </div>
</CvSection>