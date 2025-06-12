- Install dependencies:

```cmd
pip install -r requirements.txt
```

- Run inference:
```cmd
py train.py --save_path ./diffusionpen_iam_model_path --style_path ./style_models/iam_style_diffusionpen.pth --train_mode sampling --sampling_mode paragraph
```