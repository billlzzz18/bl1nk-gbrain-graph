# bl1nk-gbrain-graph

Vercel companion UI for the GBrain knowledge graph. It reads the Supabase read-model views `knowledge_graph_nodes` and `knowledge_graph_live_edges` through PostgREST.

## Required Vercel environment variables

- `SUPABASE_URL`
- `SUPABASE_ANON_KEY`

The current static build expects the deployment pipeline to replace `%%SUPABASE_URL%%` and `%%SUPABASE_ANON_KEY%%` at deploy time, or a later build step can be added.
