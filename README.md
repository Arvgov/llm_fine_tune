# Fine Tuning an LLM
This project uses LoRa to effeciently fine tune a GPT2 model with a quote database such that the model learns to output tags after it sees a "->" symbol

Here is an example at inference time:
The input is:

“Life is like a box of chocolates, you never know what you are gonna get” ->: 

The model completes with:
 “Life is like a box of chocolates, you never know what you are gonna get” ->: vernacular, love, humor, humorism, humorism-inspirational-life, humorism-inspirational
