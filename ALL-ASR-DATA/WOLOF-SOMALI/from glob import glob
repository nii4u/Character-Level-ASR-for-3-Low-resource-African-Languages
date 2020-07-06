from glob import glob
import os
from shutil import copy2


source_path = '/content/drive/My Drive/ASR-Data/Data-Collection-ASR/Data'
destination_path = '/content/drive/My Drive/ASR-Data/Data-Collection-ASR/Audio'

for portion in ['TRAIN', 'TEST', 'VALIDATION']:
    all_audios = glob(os.path.join(source_path, portion) + '/*/*.wav')
    for audio_name in all_audios:
        source_audio = os.path.join(source_path, portion, audio_name)
        # print('destination_path:', destination_path)
        des_audio = os.path.join(destination_path, portion)
    #     print('source_path:', source_audio)
    #     print('des_audio:', des_audio)
    #     break
    # break
        copy2(source_audio, des_audio)