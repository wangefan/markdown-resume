run under windows

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t readable resume.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t readable ps.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t blockish resume.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t modern resume.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t roboto resume.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t swissen resume.md ./

docker run -v "%cd%":/resume there4/markdown-resume md2resume pdf -t unstyled resume.md ./