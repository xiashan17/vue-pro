
<script>
import { store } from 'vuex'
const Counter = {
    template: `<div>{{ count }}</div>`,
    computed: {
        count () {
            return store.state.count;
        }
    }
}
</script>
