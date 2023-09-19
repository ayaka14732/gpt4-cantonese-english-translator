# GPT-4 Cantonese-English Translator

A Cantonese-English translator based on prompt engineering.

## Usage

```sh
export OPENAI_API_KEY='sk-...'
```

```python
>>> from lib import en2yue, yue2en
>>> yue2en('個勾唔夠力㗎，唔好掛件大褸上去。')
"The hook is not strong enough, don't hang a coat on it."
>>> en2yue("Don't hang an overcoat—the hook can't hold it.")
'唔好掛大褸，掛鈎承唔住。'
```
