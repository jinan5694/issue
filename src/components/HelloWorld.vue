<script>
export default {
  name: 'HelloWorld',
  render (h) {
    // return h('div', 'hello world') is ok

    // [Vue warn]: Failed to mount component: template or render function not defined.
    return h(<div>hello world</div>)
  },
  props: {
    msg: String
  }
}
</script>

