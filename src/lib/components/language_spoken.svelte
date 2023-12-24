<script>
	import SkillsPill from "./skills_pill.svelte";

</script>

<SkillsPill>
    <h3>
        <slot name='emoji'/> <slot name='language'/> <span class='font-normal'><slot name='level'/></span>
    </h3>
</SkillsPill>