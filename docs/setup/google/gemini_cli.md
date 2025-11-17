### Gemini CLI

## 1. Install Gemini CLI on your computer.  
Guide : https://github.com/google-gemini/gemini-cli  

### 2. Set mcp server for gemini  
make .gemini/settings.json in your unreal project root  .  
Json content is below.   
- Port numbers may vary. Check the isekai scroll.
- Name the server whatever you want.  In the example, it is called UE_AI.  
```
{
  "mcpServers": {
    "UE_AI": {
	    "httpUrl": "http://127.0.0.1:8708/mcp"
      }
    }
}

```


### 3. Run gemini in your project  
```
$gemini
```
Check if the mcp server is registered.  
Enter '/mcp' in the gemini console.  

![](https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai/blob/main/docs/images/gemini_mcp_example.png)

### [Goto Next Step : How to use](https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai/blob/main/docs/howtouse/howtouse.md)  
### [Goto Main](https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai)
