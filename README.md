# 10-Steps Poem Summarization using IBM Granite-3.3B-Instruct
# Project Overview
This project utilizes the IBM Granite-3.3B-Instruct model, integrated via Replicate and LangChain, to create structured summaries of poems following a 10-step methodology inspired by MyEssayWriter.ai's guide on poem summarization. The project processes poems from the Kaggle Poem Dataset, generating summaries that capture key themes, imagery, and narratives through a systematic approach.
Raw Dataset

# Source: Kaggle Poem Dataset by Maruf Chowdhury, comprising two CSV files: Poems_Dataset.csv and poemDatasetWithSummary.csv, containing poem texts, titles, and summaries.
Access: Available at DOI: 10.34740/kaggle/dsv/7981215 on Kaggle.
License: Refer to the Kaggle dataset page for specific licensing details (typically CC BY-SA 4.0 for Kaggle datasets, but verify on the dataset page).

# Insights & Findings

- The IBM Granite-3.3B-Instruct model effectively generates concise and structured poem summaries, adhering to the 10-step methodology, which includes summarizing stanzas, highlighting key words, and using metaphors.
- For the first poem, the model captured the stormy, melancholic setting and the theme of love amidst hardship, though it elaborated beyond the ground truth's brevity.
- For "The Road Not Taken," the model accurately reflected the poem's focus on choice and its consequences, aligning closely with the provided ground truth while adding nuanced interpretations.
- The structured 10-step approach enhances the depth of analysis, making summaries more comprehensive than simpler prompts, though it may introduce slight deviations from the original dataset summaries.
- The Granite model generates detailed 10-step summaries, capturing themes, imagery, and narratives, though concise prompts are crucial to avoid truncation.
- Short prompts and reduced context tokens improve output completeness, particularly for complex 10-step summaries.

# AI Support Explanation
The project employs the IBM Granite-3.3B-Instruct model, accessed through the Replicate API and integrated with LangChain for efficient prompt handling. The model processes poem content to produce summaries in various formats, from single-sentence overviews to detailed 10-step analyses, leveraging natural language understanding to interpret themes, imagery, and narratives. The methodology ensures consistent output by structuring prompts to focus on specific aspects like setting, story, and key quotes, enhancing interpretability and depth.
