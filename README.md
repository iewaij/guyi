# 故意背单词
用机器学习算法识别网页和字幕中的生词。
Deliberately learn vocabulary from web pages and video subtitles.

## Workflow with Vocabulary.com
用 vocabulary.com 的全文抓取可以快速实现生词识别，我制作了一个 workflow 实现从网页、文件、文字中抓取内容。具体实现可参考我的[推文](https://twitter.com/tiewuz/status/976509852502642688)。

[故意背单词 v0.1 on workflow](https://workflow.is/workflows/bb981f6b23f44686b719dace8ec87120)

## Roadmap
### Prototype Stage 0
- [ ] Predict level of learner
- [ ] Apply Zipf's Law to detect vocabulary
- [ ] Export vocabulary to dictionary or Quizlet
- [ ] Strip content from web pages or subtitles through Python CLI
- [ ] Adding vocabulary to quizlet through API
- [ ] Export vocabulary to Eudic
- [ ] Wrap
### Prototype Stage 1
- [ ] Build web API
- [ ] Integrate with workflow
