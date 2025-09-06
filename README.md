# Vision Moderation Mcp Server
A Model context Protocal(MCP) Server for images or videos and their related text infomation moderation.

Issues to be detected includes: Nudity or Sexual Activities, Violence and Gore, Minor Safety, Integrity & Authenticity, Illegal Activity and Regulated Goods, Hateful behavior, Harassment & Bullying, Fraudulent Behavior and etc as well as their confidence scores.

## MCP tools
#### 1. images_moderation
Detect issues of given image_urls and their relatet text information. If no text information, please give empty string. The response will be a dict with each issue detected and its confidence score. If no issue detected, response will return with a dict with key "Normal" and its score.

#### 2. video_moderation
Detect issues of given a video_url and their relatet text information. If no text information, please give empty string. The response will be a dict with each issue detected and its confidence score. If no issue detected, response will return with a dict with key "Normal" and its score.
