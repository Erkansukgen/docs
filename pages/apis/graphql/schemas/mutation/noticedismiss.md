---
toc: false
---
<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  noticeDismiss
  <a href="/docs/apis/graphql/schemas/object/noticedismisspayload" class="pill pill--object pill--normal-case pill--large" title="Go to OBJECT NoticeDismissPayload"><code>NoticeDismissPayload</code></a>

</h1>
<!-- vale on -->


<p>Dismisses a notice from the Buildkite UI. This mutation is idempotent so if you dismiss the same notice multiple times, it will return the original <code>dismissedAt</code> time</p>


<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Arguments</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>input</code><a href="/docs/apis/graphql/schemas/input_object/noticedismissinput" class="pill pill--input_object pill--normal-case pill--medium" title="Go to INPUT_OBJECT NoticeDismissInput"><code>NoticeDismissInput</code></a></h3><p>Parameters for NoticeDismiss</p></td></tr>
  </tbody>
</table>
