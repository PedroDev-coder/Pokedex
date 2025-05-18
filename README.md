# Pokedex - Parte 1

## 📄 Descrição
---

## 🧩 Componente 1 - Responsividade do Banner com CSS FlexBox

Neste componente, foi desenvolvida a **responsividade do banner principal** do site da Pokédex, utilizando **CSS FlexBox** para criar um layout dinâmico, adaptável e centrado, sem a necessidade de múltiplas media queries.

### 🔍 Desafio proposto
O objetivo foi tornar o banner da Pokédex responsivo, garantindo que ele se ajustasse automaticamente a diferentes larguras de tela e comportasse de **1 até 5 cards**, dependendo do espaço disponível.

### 🛠️ Tecnologias e conceitos aplicados
- CSS FlexBox (`display: flex`, `flex-wrap: wrap;`)
- Gap para espaçamento entre elementos
- Layout responsivo sem necessidade de media queries
- Design centrado com `justify-content: center`
- Abordagem mobile-first e de fácil manutenção

### 📐 Implementação do layout

```css
.pokedex {
  padding: 1rem;
  display: flex;
  flex-wrap: wrap;
  gap: 2rem 2rem;
  justify-content: center;
}

.pokedex > * {
  flex: 0 0 250px;
}
