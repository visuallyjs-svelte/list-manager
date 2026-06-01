<script>

	import { SurfaceComponent, ControlsComponent} from "@visuallyjs/browser-ui-svelte"

    import renderOptions from "./render-options"
    import viewOptions from "./view-options"
    import modelOptions from "./model-options"

</script>

<div class="vjs-list-manager">
	<SurfaceComponent renderOptions={renderOptions} viewOptions={viewOptions} modelOptions={modelOptions} url="/dataset.json">
		<ControlsComponent/>
	</SurfaceComponent>
</div>
