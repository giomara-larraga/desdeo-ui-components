<script module>
import { defineMeta } from '@storybook/addon-svelte-csf';

import { Button } from '../lib/components/ui/button/index.js';
	import { Label } from 'bits-ui';

 const { Story } = defineMeta({
    title: 'MyComponent',
    component: Button,

  });
</script>

<Story name="Default" args={{ variant: "default", size: "default" }} tags={['autodocs']}>
  {#snippet children(args)}
    <Button {...args}>Reactive component</Button>
  {/snippet}
</Story>
