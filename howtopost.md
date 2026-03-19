## Prerequisites
1. Clone this repo.
2. Install Hexo. Follow the instruction [here](https://hexo.io/docs/)

## Create a new episode
1. Upload the audio file into Cloudflare and get its URL.
2. [Optional] Create timeline entry. Follow the timeline generation tool instruction.
3. Run `hexo new [ep name]`. The file will be under `source/_posts`.
4. Take `ep1.md` as a reference, fill in needed metadata in the new Markdown file.
   - `title`
   - `date`: publish date
   - `tags`
   - `excerpt`: if needed new line in excerpt, use `<br>`
   - `podcast`
     - `duration`: in seconds
     - `media` - `url`: url to the podcast
     - `chapters`: timeline. If no timeline, just leave blank and don't reference it in the main part of the markdown.
     - `references`: references in the episode. If no reference, just leave blank and don't reference it in the main part of the markdown.
5. Fill in the body of the markdown as needed.

## Test the website
1. Run `hexo server`
2. Navigate to the `localhost` and inspect the outcome.

## Publish
1. Simply push the changes to the repo.
2. Website building can be monitored on the github repo page -> `Actions` tab.

## For more information
The Hexo theme is [Chromate](https://github.com/guiqiqi/chromate). Their readme have more information. 