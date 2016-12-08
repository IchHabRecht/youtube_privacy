# TYPO3 Extension "youtube_privacy"

This extension ensures your YouTube videos are rendered using the "nocookie" privacy feature.
This means the source urls of the videos are using the https://www.youtube-nocookie.com/ domain by default.
Furthermore you can enable or disable the display of related videos at the end of the video.

## Installation

- install and activate this extension
- include the provided static template

## Usage

The extension extends the TypoScript of fluid_styled_content.
You can find the privacy settings in `lib.fluidContent.settings.media.privacy`:
- nocookie: enable or disable the usage of www.youtube-nocookie.com base url
- rel: enable or disable the display of related videos at the end
