# PublicGPTService
PublicGPTService || Free GPT3 API || Darkmash

<img src="https://komarev.com/ghpvc/?username=merwin-gpt&label=Project%20Views-Github&color=0e75b6&style=flat" alt="darkmash-org" /> 



  <h4>Public GPT API ~ by darkmash<br></h4>

<h6>V 1.0.0</h6>
  <hr>

- Public API url : https://main--publicgptservice.repl.co/generate


<b>/generate</b> [Get] - > <i>generate reply,<br>

  You can pass in the prompt in<br>
  the prompt header..<br>
  And you get json response.. Like : <br><br></i>
  

```json
  {
  "return" : "[gpt's response]"
  }
```

<hr>

  <b>Using curl :</b>

```sh
  curl -i -H "Accept: application/json" -H "prompt: [what you wanna ask]"  https://main--publicgptservice.repl.co/generate
```  

### To run localy 
- (currently only works on linux/macOS): 
- This will start a local API at "http://127.0.0.1:5000/"

```sh
git clone https://github.com/darkmash-org/PublicGPTService.git
```

```sh
cd PublicGPTService
```

```sh
python main.py # use python3 if python is python2 (the code only work on python3)
```
