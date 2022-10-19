+++

title = "76%"
summary = "out of 100,000 analyzed apps contain obfuscated strings."
weight = 1
+++

An analysis using the tool StringHound showed that obfuscated strings hide: 

- critical usages of URLs 
- piggy-backed permissions
- insecure cryptography algorithms
- hard-coded credentials 
- dangerous services
- root commands
- API keys

Ad libraries are responsible for over 63% of obfuscated strings. Queryella does flag obfuscated privacy violations while other virus scanners fail to do so.