# reels-assets

Short-lived static hosting for the [that.sounds.amazing](https://instagram.com/that.sounds.amazing)
render engine (Innova Marketing LLC).

Instagram's Content Publishing API fetches a video by URL ("we cURL the video using the
passed-in URL, so it must be on a public server"). This repo is that public server: the
engine commits one MP4 to `videos/`, waits for the GitHub Pages deploy, hands Instagram the
URL, and deletes the file again once the post has a permalink.

Nothing here is a product, a download, or a service. It is a staging area that is usually empty.
