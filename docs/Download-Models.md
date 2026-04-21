<table>
  <tr align="center">
    <th>Architecture</th>
    <th>Checkpoint</th>
    <th>UNet / DiT</th>
    <th>Text Encoder</th>
    <th>VAE</th>
  </tr>
  <tr align="center">
    <td><b>SD1</b></td>
    <td><a href="https://civitai.com/models">CivitAI</a></td>
    <td>N/A</td>
    <td>N/A</td>
    <td><a href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors">vae-ft-mse-840000</a></td>
  </tr>
  <tr align="center">
    <td><b>SDXL</b></td>
    <td><a href="https://civitai.com/models">CivitAI</a></td>
    <td>N/A</td>
    <td>N/A</td>
    <td><a href="https://huggingface.co/madebyollin/sdxl-vae-fp16-fix/blob/main/sdxl_vae.safetensors">sdxl-vae-fp16-fix</a></td>
  </tr>
  <tr>
    <td align="center"><b>Lumina-Image-2.0</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/neta-art/Neta-Lumina/blob/main/neta-lumina-v1.0-all-in-one.safetensors">Neta-Lumina</a></li>
        <li><a href="https://huggingface.co/duongve/NetaYume-Lumina-Image-2.0/blob/main/NetaYume_v4_all_in_one.safetensors">NetaYume-Lumina</a></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/neta-art/Neta-Lumina/blob/main/Unet/neta-lumina-v1.0.safetensors">Neta-Lumina</a></li>
        <li><a href="https://huggingface.co/duongve/NetaYume-Lumina-Image-2.0/blob/main/Unet/v4/NetaYumev4_unet.safetensors">NetaYume-Lumina</a></li>
      </ul>
    </td>
    <td align="center">
      <p>
        <ins><b>gemma_2_2b</b></ins>
      </p>
      <a href="https://huggingface.co/duongve/NetaYume-Lumina-Image-2.0/blob/main/Text_Encoder/gemma_2_2b_fp16.safetensors">fp16</a>
    </td>
    <td rowspan="5" align="center">
      <p>
        <ins><b>Flux</b></ins>
      </p>
      <a href="https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors">ae</a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Flux-Dev</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/flux1-dev/blob/main/flux1-dev-fp8.safetensors">fp8</a></li>
        <li><a href="https://huggingface.co/lllyasviel/flux1-dev-bnb-nf4/blob/main/flux1-dev-bnb-nf4-v2.safetensors">bnb-nf4-v2</a></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/black-forest-labs/FLUX.1-Krea-dev/blob/main/flux1-krea-dev.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/QuantStack/FLUX.1-Krea-dev-GGUF/tree/main">gguf</a></li>
        <li><a href="https://huggingface.co/nunchaku-tech/nunchaku-flux.1-krea-dev/tree/main">nunchaku</a></li>
      </ul>
    </td>
    <td rowspan="2">
      <ul>
        <li><a href="https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors">clip_l</a></li>
      </ul>
      <p align="center">
        <ins><b>t5xxl</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp16.safetensors">fp16</a></li>
        <li><a href="https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors">fp8_scaled</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Flux-Kontext</b></td>
    <td rowspan="10" align="center">N/A</td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/flux1-kontext-dev_ComfyUI/blob/main/split_files/diffusion_models/flux1-dev-kontext_fp8_scaled.safetensors">fp8_scaled</a></li>
        <li><a href="https://huggingface.co/QuantStack/FLUX.1-Kontext-dev-GGUF/tree/main">gguf</a></li>
        <li><a href="https://huggingface.co/nunchaku-tech/nunchaku-flux.1-kontext-dev/tree/main">nunchaku</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Z-Image</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/z_image/blob/main/split_files/diffusion_models/z_image_bf16.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/jayn7/Z-Image-GGUF/tree/main">gguf</a></li>
      </ul>
    </td>
    <td rowspan="3">
      <p align="center">
        <ins><b>qwen_3_4b</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/z_image_turbo/blob/main/split_files/text_encoders/qwen_3_4b.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/jiangchengchengNLP/qwen3-4b-fp8-scaled/blob/main/qwen3_4b_fp8_scaled.safetensors">fp8_scaled</a></li>
        <li><a href="https://huggingface.co/Qwen/Qwen3-4B-GGUF/tree/main">gguf</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Z-Image-Turbo</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/z_image_turbo/blob/main/split_files/diffusion_models/z_image_turbo_bf16.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/jayn7/Z-Image-Turbo-GGUF/tree/main">gguf</a></li>
        <li><a href="https://huggingface.co/nunchaku-tech/nunchaku-z-image-turbo/tree/main">nunchaku</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Flux.2-Klein 4B</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/black-forest-labs/FLUX.2-klein-4B/blob/main/flux-2-klein-4b.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/black-forest-labs/FLUX.2-klein-4b-fp8/blob/main/flux-2-klein-4b-fp8.safetensors">fp8_scaled</a></li>
      </ul>
    </td>
    <td rowspan="3" align="center"><a href="https://huggingface.co/Comfy-Org/vae-text-encorder-for-flux-klein-9b/blob/main/split_files/vae/flux2-vae.safetensors">flux2-vae</a></td>
  </tr>
  <tr>
    <td align="center"><b>Flux.2-Klein 9B</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/black-forest-labs/FLUX.2-klein-9B/blob/main/flux-2-klein-9b.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/black-forest-labs/FLUX.2-klein-9b-fp8/blob/main/flux-2-klein-9b-fp8.safetensors">fp8_scaled</a></li>
      </ul>
    </td>
    <td>
      <p align="center">
        <ins><b>qwen_3_8b</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/vae-text-encorder-for-flux-klein-9b/blob/main/split_files/text_encoders/qwen_3_8b.safetensors">bf16</a></li>
        <li><a href="https://huggingface.co/Comfy-Org/vae-text-encorder-for-flux-klein-9b/blob/main/split_files/text_encoders/qwen_3_8b_fp8mixed.safetensors">fp8mixed</a></li>
        <li><a href="https://huggingface.co/Qwen/Qwen3-8B-GGUF/tree/main">gguf</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Ernie-Image</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/ERNIE-Image/tree/main/diffusion_models">bf16</a></li>
        <li><a href="https://huggingface.co/Bedovyy/ERNIE-Image-Quantized/tree/main">fp8_scaled</a></li>
      </ul>
    </td>
    <td>
      <p align="center">
        <ins><b>ministral-3-3b</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/ERNIE-Image/blob/main/text_encoders/ministral-3-3b.safetensors">bf16</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Wan 2.2 T2V</b></td>
    <td>
      <ul>
        <li>
          <b>[HN]</b>
          <a href="https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_t2v_high_noise_14B_fp8_scaled.safetensors">fp8_scaled</a>
        </li>
        <li><b>[LN]</b> <a href="https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_t2v_low_noise_14B_fp8_scaled.safetensors">fp8_scaled</a></li>
        <li><b>[HN]</b> <a href="https://huggingface.co/QuantStack/Wan2.2-T2V-A14B-GGUF/tree/main/HighNoise">gguf</a></li>
        <li><b>[LN]</b> <a href="https://huggingface.co/QuantStack/Wan2.2-T2V-A14B-GGUF/tree/main/LowNoise">gguf</a></li>
      </ul>
    </td>
    <td rowspan="2">
      <p align="center">
        <ins><b>umt5_xxl</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/text_encoders/umt5_xxl_fp16.safetensors">fp16</a></li>
        <li><a href="https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/text_encoders/umt5_xxl_fp8_e4m3fn_scaled.safetensors">fp8_scaled</a></li>
      </ul>
    </td>
    <td rowspan="2" align="center"><a href="https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/vae/wan_2.1_vae.safetensors">wan_2.1_vae</a></td>
  </tr>
  <tr>
    <td align="center"><b>Wan 2.2 I2V</b></td>
    <td>
      <ul>
        <li>
          <b>[HN]</b>
          <a href="https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_i2v_high_noise_14B_fp8_scaled.safetensors">fp8_scaled</a>
        </li>
        <li><b>[LN]</b> <a href="https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_i2v_low_noise_14B_fp8_scaled.safetensors">fp8_scaled</a></li>
        <li><b>[HN]</b> <a href="https://huggingface.co/QuantStack/Wan2.2-I2V-A14B-GGUF/tree/main/HighNoise">gguf</a></li>
        <li><b>[LN]</b> <a href="https://huggingface.co/QuantStack/Wan2.2-I2V-A14B-GGUF/tree/main/LowNoise">gguf</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Qwen-Image</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/diffusion_models/qwen_image_fp8_e4m3fn.safetensors">fp8</a></li>
        <li><a href="https://huggingface.co/city96/Qwen-Image-gguf/tree/main">gguf</a></li>
        <li><a href="https://huggingface.co/nunchaku-tech/nunchaku-qwen-image/tree/main">nunchaku</a></li>
      </ul>
    </td>
    <td rowspan="2">
      <p align="center">
        <ins><b>qwen_2.5_vl_7b</b></ins>
      </p>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/text_encoders/qwen_2.5_vl_7b_fp8_scaled.safetensors">fp8_scaled</a></li>
        <li><a href="https://huggingface.co/unsloth/Qwen2.5-VL-7B-Instruct-GGUF/tree/main">gguf</a></li>
      </ul>
    </td>
    <td rowspan="3" align="center"><a href="https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/vae/qwen_image_vae.safetensors">qwen_image_vae</a></td>
  </tr>
  <tr>
    <td align="center"><b>Qwen-Image-Edit</b></td>
    <td>
      <ul>
        <li><a href="https://huggingface.co/Comfy-Org/Qwen-Image-Edit_ComfyUI/blob/main/split_files/diffusion_models/qwen_image_edit_2509_fp8_e4m3fn.safetensors">fp8</a></li>
        <li><a href="https://huggingface.co/QuantStack/Qwen-Image-Edit-2509-GGUF/tree/main">gguf</a></li>
        <li><a href="https://huggingface.co/nunchaku-tech/nunchaku-qwen-image-edit-2509/tree/main/lightning-251115">nunchaku</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Anima</b></td>
    <td align="center"><a href="https://huggingface.co/circlestone-labs/Anima/blob/main/split_files/diffusion_models/anima-preview2.safetensors">bf16</a></td>
    <td align="center">
      <p>
        <ins><b>qwen_3_0.6b</b></ins>
      </p>
      <a href="https://huggingface.co/circlestone-labs/Anima/blob/main/split_files/text_encoders/qwen_3_06b_base.safetensors">bf16</a>
    </td>
  </tr>
</table>

> [!Tip]
> - Put **Checkpoint** / **UNet** / **DiT** in `~webui\models\Stable-diffusion`
> - Put **Text Encoders** in `~webui\models\text_encoder`
> - Put **VAE** in `~webui\models\VAE`

> [!Note]
> To use the **GGUF** version of `qwen_2.5_vl_7b` for `img2img`, you need to download and select the `mmproj` file too

> [!Important]
> For **Nunchaku**, download the `fp4` version when using a RTX 50+ GPU ; otherwise download the `int4` version
