# About me

``from dataclasses import dataclass, field
from typing import Dict, List

@dataclass
class Expertise(Me):
  name: str = 'Maxim Matvejev'
  bachelor: str = 'HSE Fundamental and Computational Linguistics'
  minor: str = 'Intellectual Data Analysis'
  thesis: Dict[str, str | List[str]] = field(default_factory=lambda: {
    'Title': 'Comparison of Rule-based and Deep Learning Models in the Context of Homonymy Resolution of Russian Bi-aspectual Verbs',
    'Data': 'Powerful web-parser for context and target token markup collection from Russian National Corpus',
    'Deep Learning': [
      'Bert-like model from scratch', 
      'Morpheme-based tokenization', 
      'Multi-Head Attention', 
      'Priority Weighting & Bias', 
      'Focal Loss', 
      'SwiGLU activation'
    ],
    'Rule-based': [
      'Contextual rules for homonymy resolution were implemented',
      'The result obtained is comparable in quality to BERT',
      'O(n) complexity',
      'Found errors in Russian National Corpus mark-up and data-driven limitations'
    ]
  })

  languages: Dict[str, str] = field(default_factory=lambda: {
    'Russian': 'Native',
    'English': 'C1',
    'German': 'A2'
  })

  code: List[str] = field(default_factory=lambda: ['python', 'sql'])
  
  technologies: Dict[str, List[str]] = field(
    default_factory=lambda: {
      'nlp': ['spacy','pymorphy2', 'pymystem3', 'nltk', 're', 'natasha', 'gensim', 'stanza'],
      'ml': ['scikit-learn', 'numpy'],
      'dl': ['pytorch', 'keras', 'transformers'],
      'analytics': ['pandas'],
      'visualization': ['seaborn', 'matplotlib', 'plotly'],
      'scraping': ['bs4', 'selenium'],
      'databases': ['postgresql'],
      'os': ['windows']
    })
  
  cv: str = 'https://docs.google.com/document/d/1SNaiJOuf3XrUo_zUvtTL52_Mir364S6L7jR4UsZt3tI/edit?usp=sharing'
  
  contacts: Dict[str, str] = field(
    default_factory=lambda: {
      'telegram': '@your_masya',
      'email': 'mmatvs@mail.ru'
    })
``
