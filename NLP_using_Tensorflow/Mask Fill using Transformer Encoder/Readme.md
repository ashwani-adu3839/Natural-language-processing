# Masked Language:
Masked Langage Model does not have access to the full input. Rather, it has access to a masked input, where some (often 10-20 percent) of the input tokens is masked. With masked, we simply mean that the token (and sometimes a span of token) is replaced with a <mask> token. The goal, then, becomes reconstructing the original sequence, i.e. to reveal what is hidden under the mask. The task adds complexity on top of a regular language model task, and some works argue that it can help boost performance.
  
  | Model Architecture |
|------------|
| <img src="https://github.com/codewithAshwani/Tensorflow_Example/blob/main/Classification/img/Concentric_circle.png" width="400"> |
