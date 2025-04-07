### Tokenizer Results

The following are the outputs of various tokenizers applied to the Bengali sentence:  
"আমি ভাত খাই। সে বাজারে যায়। তিনি কি সত্যিই ভালো মানুষ?"

#### Tokenizer: `ai4bharat/indic-bert`
- **Vocab Size**: 200,000
- **Pad Token ID**: 0
- **Mask Token ID**: 4
- **Special Tokens**:  
  ```json
  {
    "bos_token": "[CLS]",
    "eos_token": "[SEP]",
    "unk_token": "<unk>",
    "sep_token": "[SEP]",
    "pad_token": "<pad>",
    "cls_token": "[CLS]",
    "mask_token": "[MASK]"
  }
  ```
- **Tokenizer Output**:  
  ```
  ['▁আম', '▁ভ', 'ত', '▁খ', 'ই', '।', '▁স', '▁বজ', 'র', '▁য', 'য', '।', '▁তন', '▁ক', '▁সত', 'য', 'ই', '▁ভল', '▁মন', 'ষ', '?']
  ```

#### Tokenizer: `sarvamai/sarvam-1`
- **Vocab Size**: 68,096
- **Pad Token ID**: None
- **Mask Token ID**: None
- **Special Tokens**:  
  ```json
  {
    "bos_token": "<s>",
    "eos_token": "</s>",
    "unk_token": "<unk>"
  }
  ```
- **Tokenizer Output**:  
  ```
  ['▁আমি', '▁ভ', 'াত', '▁খ', 'াই', '।', '▁সে', '▁বাজ', 'ারে', '▁যা', '<0xE0>', '<0xA7>', '<0x9F>', '।', '▁তিনি', '▁কি', '▁সত্যিই', '▁ভালো', '▁মানুষ', '?']
  ```

#### Tokenizer: `google/gemma-3-1b-pt`
- **Vocab Size**: 262,144
- **Pad Token ID**: 0
- **Mask Token ID**: None
- **Special Tokens**:  
  ```json
  {
    "bos_token": "<bos>",
    "eos_token": "<eos>",
    "unk_token": "<unk>",
    "pad_token": "<pad>",
    "boi_token": "<start_of_image>",
    "eoi_token": "<end_of_image>",
    "image_token": "<image_soft_token>"
  }
  ```
- **Tokenizer Output**:  
  ```
  ['আমি', '▁ভাত', '▁খাই', '।', '▁সে', '▁বাজারে', '▁যায়', '।', '▁তিনি', '▁কি', '▁সত্যিই', '▁ভালো', '▁মানুষ', '?']
  ```

#### Tokenizer: `google/gemma-2b`
- **Vocab Size**: 256,000
- **Pad Token ID**: 0
- **Mask Token ID**: None
- **Special Tokens**:  
  ```json
  {
    "bos_token": "<bos>",
    "eos_token": "<eos>",
    "unk_token": "<unk>",
    "pad_token": "<pad>",
    "additional_special_tokens": ["<start_of_turn>", "<end_of_turn>"]
  }
  ```
- **Tokenizer Output**:  
  ```
  ['আ', 'মি', '▁ভ', 'াত', '▁খ', 'াই', '।', '▁সে', '▁ব', 'াজ', 'ার', 'ে', '▁য', 'ায়', '।', '▁ত', 'িনি', '▁কি', '▁স', 'ত', '্য', 'ি', 'ই', '▁ভ', 'াল', 'ো', '▁মান', 'ু', 'ষ', '?']
  ```

#### Tokenizer: `ai4bharat/indictrans2-en-indic-1B`
- **Vocab Size**: 32,322
- **Pad Token ID**: 1
- **Mask Token ID**: None
- **Special Tokens**:  
  ```json
  {
    "bos_token": "<s>",
    "eos_token": "</s>",
    "unk_token": "<unk>",
    "pad_token": "<pad>"
  }
  ```
- **Tokenizer Output**:  
  ```
  ['▁', 'আ', 'ম', 'ি', '▁', 'ভ', 'া', 'ত', '▁', 'খ', 'া', 'ই', '।', '▁', 'স', 'ে', '▁', 'ব', 'া', 'জ', 'া', 'র', 'ে', '▁', 'য', 'া', 'য', '়', '।', '▁', 'ত', 'ি', 'ন', 'ি', '▁', 'ক', 'ি', '▁', 'স', 'ত', '্', 'য', 'ি', 'ই', '▁', 'ভ', 'া', 'ল', 'ো', '▁', 'ম', 'া', 'ন', 'ু', 'ষ', '?']
  ```

---
