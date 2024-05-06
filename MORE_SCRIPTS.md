## More scripts

![monalisa_free_style](assets/monalisa_more_control.gif)

## Adjust face location and face scale

```
python ./code/demo.py \
    --infer_type 'mfcc_full_control' \
    --stage1_checkpoint_path 'ckpts/stage1.ckpt' \
    --stage2_checkpoint_path 'ckpts/stage2_more_controllable.ckpt' \
    --test_image_path 'test_demos/portraits/monalisa.jpg' \
    --test_audio_path 'test_demos/audios/english_female.wav' \
    --result_path 'results/monalisa_free_style_face_location_0.1_0.5_0.4/' \
    --control_flag True \
    --seed 0 \
    --pose_yaw 0.1 \
    --pose_pitch 0 \
    --pose_roll 0 
    --face_location 0.5 \
    --face_scale 0.4
```


### Adjust head location to the left

```
python ./code/demo.py \
    --infer_type 'mfcc_full_control' \
    --stage1_checkpoint_path 'ckpts/stage1.ckpt' \
    --stage2_checkpoint_path 'ckpts/stage2_more_controllable.ckpt' \
    --test_image_path 'test_demos/portraits/monalisa.jpg' \
    --test_audio_path 'test_demos/audios/english_female.wav' \
    --result_path 'results/monalisa_free_style_face_location_0.1_0.4_0.4/' \
    --control_flag True \
    --seed 0 \
    --pose_yaw 0.1 \
    --pose_pitch 0 \
    --pose_roll 0 \
    --face_location 0.4 \
    --face_scale 0.4
```

### Adjust head location to the right

```
python ./code/demo.py \
    --infer_type 'mfcc_full_control' \
    --stage1_checkpoint_path 'ckpts/stage1.ckpt' \
    --stage2_checkpoint_path 'ckpts/stage2_more_controllable.ckpt' \
    --test_image_path 'test_demos/portraits/monalisa.jpg' \
    --test_audio_path 'test_demos/audios/english_female.wav' \
    --result_path 'results/monalisa_free_style_face_location_0.1_0.6_0.4/' \
    --control_flag True \
    --seed 0 \
    --pose_yaw 0.1 \
    --pose_pitch 0 \
    --pose_roll 0 \
    --face_location 0.6 \
    --face_scale 0.4
```


### Adjust head to larger scale

```
python ./code/demo.py \
    --infer_type 'mfcc_full_control' \
    --stage1_checkpoint_path 'ckpts/stage1.ckpt' \
    --stage2_checkpoint_path 'ckpts/stage2_more_controllable.ckpt' \
    --test_image_path 'test_demos/portraits/monalisa.jpg' \
    --test_audio_path 'test_demos/audios/english_female.wav' \
    --result_path 'results/monalisa_free_style_face_location_0.1_0.5_0.6/' \
    --control_flag True \
    --seed 0 \
    --pose_yaw 0.1 \
    --pose_pitch 0 \
    --pose_roll 0  \
    --face_location 0.5 \
    --face_scale 0.6
```



### Adjust head to smaller scale

```
python ./code/demo.py \
    --infer_type 'mfcc_full_control' \
    --stage1_checkpoint_path 'ckpts/stage1.ckpt' \
    --stage2_checkpoint_path 'ckpts/stage2_more_controllable.ckpt' \
    --test_image_path 'test_demos/portraits/monalisa.jpg' \
    --test_audio_path 'test_demos/audios/english_female.wav' \
    --result_path 'results/monalisa_free_style_face_location_0.1_0.5_0.2/' \
    --control_flag True \
    --seed 0 \
    --pose_yaw 0.1 \
    --pose_pitch 0 \
    --pose_roll 0  \
    --face_location 0.5 \
    --face_scale 0.2
```