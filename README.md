# Downloads for Shapenet

- [ShapeNet in HuggingFace](https://huggingface.co/ShapeNet)

## Setting HF_TOKEN

```bash
export HF_TOKEN="hf_<your_huggingface_token>"
```

## Downloads

- [ShapeNetCore](https://huggingface.co/datasets/ShapeNet/ShapeNetCore)

```bash
mkdir shapenet_core
cd shapenet_core
sh ../scripts/download_shapenet_core.sh
```

- [ShapeSplatsV1](https://huggingface.co/datasets/ShapeNet/ShapeSplatsV1)

```bash
mkdir shapenet_splats
cd shapenet_splats
sh ../scripts/download_shapenet_splats_v1.sh
```
