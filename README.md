# sample-prompts

Large input (512 tokens), small output (64 tokens): Summarization use case [source](https://s3.amazonaws.com/static.nicic.gov/Videos/033438/033438-transcript.txt)
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ashivadi/sample-prompts/main/512in20out.txt)"
```

small input (64 tokens), large output (512 tokens): text generation use case [source](https://contently.net/2023/03/29/trends/chatgpt-prompts-for-writers/#:~:text=I%E2%80%99m%20a%20fashion%20blogger%20and%20I%20need%20your%20help%20writing%20a%20blog%20post.%20The%20topic%20is%20New%20York%20Fashion%20Week.%20This%20post%20should%20be%20helpful%20for%20people%20who%20are%20interested%20in%20the%20spring%20Christian%20Dior%20line)

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ashivadi/sample-prompts/main/20in512out.txt)"
```
