<script lang="ts">
  import "../app.css";

  import * as Accordion from "$lib/components/ui/accordion/index.js";
  import * as Alert from "$lib/components/ui/alert/index.js";
  import { Button, buttonVariants } from "$lib/components/ui/button/index.js";
  import * as Card from "$lib/components/ui/card/index.js";
  import * as Select from "$lib/components/ui/select/index.js";
  import { Input } from "$lib/components/ui/input/index.js";
  import { Label } from "$lib/components/ui/label/index.js";
  import { Checkbox } from "$lib/components/ui/checkbox/index.js";
  import * as Dialog from "$lib/components/ui/dialog/index.js";
  import * as DropdownMenu from "$lib/components/ui/dropdown-menu/index.js";
  import * as RadioGroup from "$lib/components/ui/radio-group/index.js";
  import { Switch } from "$lib/components/ui/switch/index.js";
  import * as Tabs from "$lib/components/ui/tabs/index.js";
  import { Toggle } from "$lib/components/ui/toggle/index.js";
  import * as ToggleGroup from "$lib/components/ui/toggle-group/index.js";
  import * as Tooltip from "$lib/components/ui/tooltip/index.js";

  let checked = false;
  let dialogOpen = false;
  let radioValue = "option1";
  let selectValue = "apple";
  let switchOn = false;
  let tabValue = "tab1";
</script>

<main>


  <!-- Button Example -->
  <Button>Button</Button>


</main>

<style>
</style>
