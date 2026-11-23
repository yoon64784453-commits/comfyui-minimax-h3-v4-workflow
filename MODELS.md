# 模型文件清单

下列文件名来自本机整合包。这里只记录文件名，不上传权重，也不把来源不明的模型冒充官方模型。工作流保存时选择的模型以「V4 使用」列标识；部分节点可能处于停用状态，实际运行以 ComfyUI 内的节点状态为准。

| 子目录 | 文件名 | V4 使用 |
| --- | --- | --- |
| `diffusion_models` | `Cobijada_H3_Hybrid_Uncensored_pruned_hybrid_int8_convrot_pruned.safetensors` | 是 |
| `diffusion_models` | `Cobijada_H3_Hybrid_Uncensored_pruned_hybrid_BF16_pruned.safetensors` | 是 |
| `diffusion_models` | `minimax_h3_hybrid_fl2va_ref2va_b25-49-int8.safetensors` | 是 |
| `diffusion_models` | `minimax_h3_image_pruned_int8_convrot.safetensors` | 否 |
| `text_encoders` | `qwen3vl_32b_minimax_h3_int8_convrot.safetensors` | 是 |
| `text_encoders` | `qwen3vl_32b_minimax_h3_nvfp4_awq.safetensors` | 否 |
| `vae` | `minimax_h3_video_vae_int8_convrot.safetensors` | 是 |
| `vae` | `minimax_h3_audio_vae_fp32.safetensors` | 是 |
| `vae` | `minimax_h3_image_vae_fp16.safetensors` | 否 |
| `latent_upscale_models` | `minimax_h3_latent_upscaler_3d_fp16_V2.safetensors` | 按节点设置 |
| `loras` | `minimax_h3_fl2v_lightx2v_turbo_4step_v0.1_comfy.safetensors` | 是 |
| `loras` | `h3-realism-people-t2v-i2v-r2v.safetensors` | 是 |
| `loras` | `H3_Combat_V2.safetensors` | 是 |
| `loras` | `Minimax H3真实电影质感V0.1.safetensors` | 是 |
| `loras` | `H3_speed_slider_1.1.safetensors` | 是 |
| `loras` | `dmad_minimax_h3_4step_full_critic_comfy.safetensors` | 是 |
| `loras` | `FrameRush-Minimax-V2_c2-st1500.safetensors` | 是 |

模型的授权、下载位置和校验值需要逐一从各发布页核实。不要仅凭文件名下载同名文件并假定权重一致。
