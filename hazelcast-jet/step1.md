

Create a Pipeline

`var p = Pipeline.create();`{{execute}}

Read items from a test source:

`var source = p.readFrom(TestSources.items(1, 2, 3));`{{execute}}

Write to a logger sink:

`source.writeTo(Sinks.logger());`{{execute}}

Submit the pipeline as a new job:

`jet.newJob(p);`{{execute}}

