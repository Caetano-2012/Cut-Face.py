<escape><h1 align="center">✂️ Detecção e Extração de Faces</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge" alt="Status Badge">
</p>

<p align="center">
  <i>Detecção de rostos e extração de faces de uma imagem utilizando OpenCV.</i><br>
  <b>Autor:</b> Caetano Bordin
</p>

---

## 🧩 Sobre o Projeto

Este projeto utiliza **OpenCV** para detectar um rosto em uma imagem e recortar a região correspondente à face. O recorte é salvo em um novo arquivo de imagem, separado da fotografia original.

## 🧰 Tecnologias Utilizadas

- **Python**
- **OpenCV (cv2)**
- **Haar Cascade** — classificador para detecção de faces.

## ⚙️ Funcionalidades

- 🖼️ Leitura da imagem `boy.jpg`;
- 🔍 Detecção de rostos;
- 🔢 Exibição da quantidade de faces detectadas;
- 🟩 Delimitação das faces com retângulos;
- ✂️ Recorte da região da face detectada;
- 💾 Salvamento do recorte como `face.jpg`.

## 📚 Aprendizados

- Detecção de faces com `detectMultiScale()`;
- Acesso a regiões específicas de uma imagem usando *slicing*;
- Extração de regiões de interesse (ROI);
- Salvamento de imagens com `cv2.imwrite()`;
- Manipulação de coordenadas e dimensões de imagens.

## 🕹️ Como Executar

1. Instale o OpenCV:

```bash
pip install opencv-python
```

2. Coloque os arquivos `boy.jpg` e `haarcascade_frontalface_default.xml` na mesma pasta do programa.

3. Execute o arquivo Python:

```bash
python main.py
```

4. O recorte da face será salvo como `face.jpg` na pasta do projeto.

## 📜 Licença

O código pode ser usado somente para **fins educacionais**.

É permitida a modificação e redistribuição, desde que os autores sejam citados e a licença original seja mantida.

O software é fornecido **"como está"**, sem garantias de qualquer tipo. Os autores não são responsáveis por danos decorrentes de seu uso.

## 👨‍💻 Autor

**Caetano Bordin**

🔗 [@Caetano-2012](https://www.github.com/Caetano-2012)

---</escape>
