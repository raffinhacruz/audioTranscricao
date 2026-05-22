Código em Python que gera audio transcrição de qualquer arquivo de áudio, de qualquer duração, separando por participante (diarização)
<br><br>
Dependências:
    pip install openai-whisper resemblyzer scikit-learn numpy
<br><br>
Observações:
<br>
    - Não precisa de token do HuggingFace.
    <br>
    - No Windows, instale também o FFmpeg e deixe o executável no PATH.
    <br>
    - O Whisper usa o FFmpeg para ler MP3/M4A/WAV etc.
    <br>
    - A diarização abaixo usa embeddings do Resemblyzer + clusterização do scikit-learn.
    <br>
