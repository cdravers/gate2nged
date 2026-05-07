# Gate 2 Acquisition Intelligence — Map

Interactive map of NGED Gate 2 grid connection projects.
Built by Last Energy. Confidential.

## Updating

After running the pipeline:

```
cd gate2-map
copy ..\gate2_tool_v7\gate2_tool\output\gate2_projects.csv gate2_projects.csv
git add gate2_projects.csv
git commit -m "refresh"
git push
```

Netlify will republish automatically within 60 seconds.
