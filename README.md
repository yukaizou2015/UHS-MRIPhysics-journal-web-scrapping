# UHS MRI Physics Team Journal Lounge

Collect journal contents for the MRI Physics Team at University Hospial Southampton NHS Foundation Trust

## Running with Docker locally for development

Inside the cloned github repo, run the following command:

```
docker run -p 4000:4000 --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:3.8 jekyll serve
```

Open the live page at http://localhost:4000/
