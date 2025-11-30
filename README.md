# **🚀 Transformer NMT — English ➜ German** #

**A custom Neural Machine Translation system built using a Transformer model from scratch in PyTorch.
Trained on the Multi30k dataset to translate English image captions into German.**

# **Key Features** #

✨ Fully custom Transformer implementation (no prebuilt modules)

🧠 Multi-Head Attention + Positional Encoding

🎯 Encoder-Decoder Architecture

🔤 Word-level tokenization

⚡ Mixed-precision training support

🧪 Custom inference for real-time translation

# **🛠 Tech Stack** #


Model	-->         PyTorch

Dataset    -->  	 HuggingFace Multi30k

Tokenizer	  -->   HF WordLevel tokenizer

Logs	    -->     TensorBoard

Hardware	   -->  GPU/CPU

#  ▶️ Quick Example #
sentence = "A young girl is playing with a dog."


translated = translate_sentence(model, tokenizer_src, tokenizer_tgt, sentence, device)


print(translated)


**Example Output:**

Ein junges Mädchen spielt mit einem Hund.


# **👤 Author** #

** Manan Dudeja **
** B.Tech CSE — VIT Chennai **

If you like this project, please ⭐ the repo! 🌟
