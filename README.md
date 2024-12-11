# Reconhecimento Facial com Python e OpenCV

Este projeto implementa um sistema de reconhecimento facial utilizando a linguagem de programação Python e a biblioteca OpenCV. Ele permite a detecção e reconhecimento de rostos em imagens ou em tempo real via câmera.

## Funcionalidades

- **Detecção de rosto**: Identificação de rostos em imagens ou vídeo.
- **Treinamento de modelo**: Construção de um modelo baseado em imagens fornecidas.
- **Reconhecimento facial**: Comparação de rostos detectados com o modelo treinado.
- **Interface amigável**: Exibição das imagens e resultados diretamente na tela.

## Pré-requisitos

Para executar este projeto, você precisará dos seguintes requisitos instalados em seu ambiente:

- Python 3.7 ou superior
- OpenCV
- NumPy

### Instalando os requisitos

Para instalar as dependências necessárias, execute:

```bash
pip install opencv-python-headless numpy
```

## Como usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/reconhecimento-facial.git
```

2. Acesse o diretório do projeto:

```bash
cd reconhecimento-facial
```

3. Execute o script de treinamento (opcional, caso deseje treinar um modelo personalizado):

```bash
python train_model.py --dataset caminho/para/imagens
```

4. Inicie o reconhecimento facial em tempo real:

```bash
python face_recognition.py
```

5. Para testar com uma imagem específica:

```bash
python face_recognition.py --image caminho/para/imagem.jpg
```

## Estrutura do projeto

```plaintext
reconhecimento-facial/
|├── train_model.py       # Script para treinamento do modelo
|├── face_recognition.py # Script principal para reconhecimento
|├── dataset/            # Diretório de imagens para treinamento
|├── models/             # Diretório para salvar o modelo treinado
|├── README.md          # Documentação do projeto
```

## Exemplos de uso

### Reconhecimento facial em uma imagem

1. Execute o script com a flag `--image`:

```bash
python face_recognition.py --image imagens/teste.jpg
```

2. O resultado será exibido na tela com os rostos identificados.

### Reconhecimento facial em tempo real

1. Conecte uma câmera ao seu dispositivo.
2. Execute o script sem argumentos:

```bash
python face_recognition.py
```

3. O vídeo da câmera será exibido com as detecções em tempo real.

## Contribuições

Sinta-se à vontade para contribuir com este projeto. Para isso:

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações:

```bash
git checkout -b minha-nova-funcionalidade
```

3. Envie um pull request para análise.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

Desenvolvido por [Seu Nome](https://github.com/seu-usuario).

---

### Observação
Certifique-se de verificar se você possui permissões para utilizar quaisquer datasets incluídos no projeto ou usados para treinamento.
