# Aula 05 - Interface Gráfica (UI) 🎨

---

## 🖼️ Views e ViewGroups
- **View**: Um componente visual (Botão, Texto, Imagem).
- **ViewGroup**: Um container que organiza as Views (Layout).

---

## 📏 Unidades de Medida
- **dp** (Density-independent Pixels): Para tamanhos e margens.
- **sp** (Scale-independent Pixels): Para textos (respeita a acessibilidade).
- **Dica**: Nunca use `px`!

---

## 📐 Layouts Principais
- **LinearLayout**: Organiza em linha ou coluna.
- **FrameLayout**: Empilha Views (uma sobre a outra).
- **ConstraintLayout**: O mais poderoso. Flexível e plano.

---

## 🎨 Estilos e Temas
- `themes.xml`: Define a aparência global.
- `styles.xml`: Reaproveita propriedades em várias Views.
- Dark Mode automático.

---

## 🍎 Auto Layout (iOS)
- No iOS, o `ConstraintLayout` é o equivalente ao `Auto Layout`.
- Ambos usam "amarras" (constraints) para definir a posição.