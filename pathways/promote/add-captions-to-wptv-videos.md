# Add Captions to WPTV Videos

Help make WordPress.tv videos accessible by adding captions or translating existing subtitles. You'll pick a video, caption it using Amara.org, and submit it for review.

- **Reference:** [Captioning guide on WordPress.tv](https://wordpress.tv/using-amara-org-to-caption-or-subtitle-a-wordpress-tv-video/) — the full process from start to finish
- **Connect:** Join [#wptv](https://wordpress.slack.com/archives/wptv) on Slack and introduce yourself

## Tools used:
- [vibe](https://thewh1teagle.github.io/vibe/) (auto-transcription)
- [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit/releases) (translation & editing))
- [GoTranscript Converter](https://gotranscript.com/subtitle-converter) (SRT → TTML)
## Steps
**Step 1 – Transcription (Vibe)**  

1. Open Vibe and load the MP4 file
2. Vibe automatically transcribes the speech in the video language
3. Download the result as an SRT file

**Step 2 – Translation (Subtitle Edit)**  
1. Open Subtitle Edit
2. `File → Open` – load the SRT
3. Run auto-translation: `Auto translate → Auto translate…`
    - Engine: Google Translate V1 (free, no API key needed)
    - Source: Video language / Target: English or any other WP language
    - Click Translate
4. Both languages appear side by side

**Step 3 – Proofreading & Corrections (Subtitle Edit)** Review and correct both tracks – the original transcription and the English translation. Automatic transcription and machine translation are not perfect, especially with proper names, technical terms, or unclear audio.  
When done, save both files separately. It's a good habit to add the language to the filename (e.g. `video_pl.srt` and `video_en.srt`) so both files are easy to tell apart.  
![:ampoule:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/1f4a1.png) If you already have two separate files (PL + EN) and want to open them together: `File → Open` (English) + `File → Open Original` (Polish)  
**Step 4 – Convert SRT → TTML (GoTranscript)**  
1. Go to [https://gotranscript.com/subtitle-converter](https://gotranscript.com/subtitle-converter)
2. Upload the SRT file
3. Select TTML as output format
4. Download the TTML file

![:information:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/2139-fe0f.png) [WordPress.org](http://WordPress.org) requires TTML format for video subtitles. Other platforms (YouTube, Vimeo, self-hosted WordPress) accept plain SRT.  
**Step 5 – Upload to** **[WordPress.org](http://WordPress.org)**  

1. **Go to the video page on** [WordPress.org](http://WordPress.org)
2. Find the subtitles/captions section for the video
3. Upload the TTML file as the subtitle track

![:information:](https://a.slack-edge.com/production-standard-emoji-assets/16.0/google-medium/2139-fe0f.png) [WordPress.org](http://WordPress.org) specifically requires **TTML** format for subtitles – SRT will not work there. For other platforms SRT is fine:  

- YouTube → SRT
- Vimeo → SRT
- Self-hosted WordPress → SRT


## Contribution checklist

- Captions uploaded to the video's WordPress.tv page
- Posted in #wptv with a link

## What happens next

A moderator will review your captions. If no response after 2–3 weeks, ask in #wptv.

When you're ready, pick another video — there are always more that need captions.

## Help

Stuck? Check the [getting help guide](https://make.wordpress.org/handbook/pathways/before-you-begin/#getting-help), then ask in [#wptv](https://wordpress.slack.com/archives/wptv).

**Further reading:**
- [WPTV Team Handbook](https://make.wordpress.org/tv/handbook/)
- [WPTV Team Blog](https://make.wordpress.org/tv/)

<div class="wp-block-wporg-sidebar-container is-floating-sidebar" data-breakpoint="1300px">
  <div class="pathway-info">
    <div class="pathway-header">
      <span class="dashicons dashicons-megaphone"></span> Promote
    </div>
    <div class="pathway-dtails">
      <p>Beginner-friendly task</p>
      <p class="newbies">New here? <a href="https://make.wordpress.org/handbook/pathways/before-you-begin/">Get set up</a> with accounts, community basics, and info on badges. →</p>
    </div>
  </div>
</div>
