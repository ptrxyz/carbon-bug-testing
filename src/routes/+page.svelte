<script lang="ts">
    import 'carbon-components-svelte/css/white.css'

    import { Dropdown } from 'carbon-components-svelte'
</script>

<Dropdown
    titleText="Contact"
    selectedId="0"
    items={[
        { id: '0', text: 'Slack' },
        { id: '1', text: 'Email' },
        { id: '2', text: 'Fax' },
    ]}
/>
