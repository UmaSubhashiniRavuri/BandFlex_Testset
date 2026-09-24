cat > README.md << 'EOF'
# BandFlex Testset

Test sets for BandFlex bandwidth extension, built from VCTK and Expresso.

## Download

- **VCTK Testset** (~2.4 GB): included in this GitHub repo (`VCTK_Testset/`)
- **Full dataset (VCTK + Expresso, ~22 GB):** hosted on Hugging Face
  👉 https://huggingface.co/datasets/UmaSubhashiniRavuri1/BandFlex_Testset

Download from Hugging Face:

    pip install -U huggingface_hub
    hf download UmaSubhashiniRavuri1/BandFlex_Testset --repo-type=dataset --local-dir BandFlex_Testset

## Structure

    VCTK_Testset/                Expresso_Testset/
      All_distortions_inputs/      All_distortions_inputs/
      Resampling_inputs/           Resampling_inputs/
      Targets/                     Targets/

## License & credits

- VCTK: CC BY 4.0 — Yamagishi et al., CSTR VCTK Corpus
- Expresso: CC BY-NC 4.0 (non-commercial use only) — Nguyen et al., Meta AI
EOF
