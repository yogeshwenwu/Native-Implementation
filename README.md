# Native-Implementation

## Prompt to run_generation.py:
> python run_generation.py -m /mnt/mydisk/yogesh/hub/models--google--gemma-2b/snapshots/9cf48e52b224239de00d483ec8eb84fb8d0f3a3a/ --prompt "In a world where artificial intelligence is transforming every aspect of human life, from automating tasks to revolutionizing scientific research and creative expression, a young developer, driven by an insatiable curiosity and an unwavering determination to push the boundaries of what is possible, embarks on an ambitious journey to create an advanced autograder system, one that not only evaluates code for correctness but also understands the logic behind each implementation, identifies inefficiencies, and provides dynamic, personalized feedback tailored to the unique learning style of each student, ensuring that no two learners receive the same generic responses but instead benefit from an AI-driven mentor capable of analyzing patterns in their mistakes, suggesting alternative approaches, and fostering a deeper understanding of fundamental programming concepts, all while integrating sophisticated natural language processing algorithms to assess short-answer" --input-tokens 32 --max-new-tokens 32 --token-latency --num-warmup 0 --num-iter 2 --deployment-mode --benchmark --native

> gemma 2b ->  /mnt/mydisk/yogesh/hub/models--google--gemma-2b/snapshots/9cf48e52b224239de00d483ec8eb84fb8d0f3a3a/

llama2 7b chat hf > -> /mnt/mydisk/yogesh/hub/Llama-2-7b-chat-hf
                    -> /mnt/mydisk/yogesh/hub/models--meta-llama--Llama-2-7b-hf/snapshots/01c7f73d771dfac7d292323805ebc428287df4f9

> gpt2 -> /mnt/mydisk/yogesh/hub/models--openai-community--gpt2/snapshots/607a30d783dfa663caf39e06633721c8d4cfcd7e