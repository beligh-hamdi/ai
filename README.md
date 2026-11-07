# ai


split -b 50M -d Qwen3-0.6B-Q4_0.gguf qwen3_

split -b 50M -d embeddinggemma-2-Q8_0.gguf embeddinggemma2_

cat qwen3_* > Qwen3-0.6B-Q4_0.gguf

cat embeddinggemma2_* > embeddinggemma-2-Q8_0.gguf
