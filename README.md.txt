
** The Path Which is placed inside the {} should be replaced wiht your directory :-

	1. --model {C:/Users/ghant/Desktop/DeepSpeech/DeepSpeech-examples/autosub/deepspeech-0.9.3-models.pbmm}
	2. --scorer {C:/Users/ghant/Desktop/DeepSpeech/DeepSpeech-examples/autosub/deepspeech-0.9.3-models.scorer}
	3. --file path of your News File {C:\Users\ghant\Desktop\DeepSpeech\DeepSpeech-examples\autosub\News_Video}.mp4 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

** Download the model and scorer files from DeepSpeech repo. The scorer file is optional, but it greatly improves inference results :-
	1. https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm
	2. wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**And this is the Executable Command :-

 python  autosub/main.py  --model C:/Users/ghant/Desktop/DeepSpeech/DeepSpeech-examples/autosub/deepspeech-0.9.3-models.pbmm  --scorer C:/Users/ghant/Desktop/DeepSpeech/DeepSpeech-examples/autosub/deepspeech-0.9.3-models.scorer  --file C:\Users\ghant\Desktop\DeepSpeech\DeepSpeech-examples\autosub\News_Video.mp4 

