**Lazarus NLP** is a collective initiative to revive the dying languages of Indonesia through speech and language technology.

<p align="center">
    <img src="https://github.com/LazarusNLP/lazarusnlp.github.io/blob/main/docs/assets/images/logo_web.png" alt="logo" width="400"/>
</p>

## Projects

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>IndoT5: T5 Language Models for the Indonesian Language</h3>
      <p>IndoT5 is a T5-based language model trained specifically for the Indonesian language. With just 8 hours of training on a limited budget, we developed a competitive sequence-to-sequence, encoder-decode model capable of fine-tuning tasks such as summarization, chit-chat, and question-answering. Despite the limited training constraints, our model is competitive when evaluated on the <a href="https://github.com/IndoNLP/indonlg">IndoNLG</a> (text generation) benchmark.</p>
    </td>
    <td valign="top" width="50%">
      <h3>Indonesian Sentence Embedding Models</h3>
      <p>We trained open-source sentence embedding models for Indonesian, enabling applications such as information retrieval (useful for retrieval-augmented generation!) semantic text similarity, and zero-shot text classification. We leverage existing pre-trained Indonesian language models like <a href="https://github.com/IndoNLP/indonlu">IndoBERT</a> and state-of-the-art unsupervised techniques and established sentence embedding benchmarks.</p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>Indonesian Natural Language Inference Models</h3>
      <p>Open-source lightweight NLI models that are competitive with larger models on IndoNLI benchmark, with significantly less parameters. We applied knowledge distillation methods to small existing pre-trained language models like IndoBERT Lite. These models offer efficient solutions for tasks requiring natural language inference capabilities while minimizing computational resources such as cross-encoder-based semantic search.</p>
    </td>
    <td valign="top" width="50%">
      <h3>Many-to-Many Multilingual Translation Models</h3>
      <p>Adapting mT5 to 45 languages of Indonesia, we developed a robust baseline model for multilingual translation for languages of Indonesia. This facilitates further fine-tuning for niche domains and low-resource languages, contributing to greater linguistic inclusivity. Our models are competitive with existing multilingual translation models on the <a href="https://github.com/IndoNLP/nusax">NusaX</a> benchmark.</p>
    </td>
  </tr>
</table>
