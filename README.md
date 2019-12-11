# vue-ts-decorator
Vue Typescript component snippet using [vue-property-decorator](https://github.com/kaorun343/vue-property-decorator)

Right now it just provide you vue-property-decorator class based component just start typing `vue-ts-decorator` in new .Vue file. This is useful for single file component.

```
    <template>
        <div class="my-component"></div>
    </template>

    <script lang="ts">
    import { Vue, Component, Prop } from 'vue-property-decorator'

    @Component({})
    export default class MyComponent extends Vue {

    }
    </script>
```

Currently it will be available globally in editor.

# How to publish
Follow https://code.visualstudio.com/api/working-with-extensions/publishing-extension

# contribution
Any contribution is welcome, please raise a PR
