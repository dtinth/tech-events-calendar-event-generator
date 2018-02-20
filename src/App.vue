<template>
  <div id="app" class="p-4 container-md">
    <h1 class="h1">Event file generator</h1>
    <form class="mt-2">
      <dl class="form-group">
        <dt><label>Title</label></dt>
        <dd>
          <input class="form-control input-block input-lg" placeholder="Event title">
        </dd>
      </dl>
      <dl class="form-group">
        <dt><label>Summary</label></dt>
        <dd>
          <textarea class="form-control input-block" style="height: 4em; min-height: 4em;" placeholder="Event summary (one line, 280 chars)"></textarea>
        </dd>
      </dl>
      <dl class="form-group">
        <dt><label>Description</label></dt>
        <dd>
          <textarea class="form-control input-block" style="height: 7em; min-height: 7em;" placeholder="Event description"></textarea>
        </dd>
      </dl>
    </form>
    <div class="mt-4">
      <div class="markdown-body">
        <pre>Result</pre>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
