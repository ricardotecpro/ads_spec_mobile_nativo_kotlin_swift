# Aula 10 - Mundo Conectado (API REST) 🌍

---

## 🔌 O que é uma API?
- O garçom entre o App e o Servidor.
- Formato **JSON** (Leve e universal).
- Verbos HTTP: `GET`, `POST`, `PUT`, `DELETE`.

---

## 🚀 Retrofit: O Padrão Ouro
- Transforma a API em uma Interface Kotlin.
- Converte JSON -> Objeto automaticamente.
- Gerencia o tempo da requisição.

---

## 📝 Contrato da API
- Mapeamento de rotas.
- `@GET`, `@POST`.
- `@Path` e `@Query` para parâmetros.
- `@Body` para enviar dados.

---

## 🔐 Permissões e Segurança
- `INTERNET` permission no Manifesto.
- HTTPS obrigatório (segurança).
- Trate o erro 404, 500 e sem internet!

---

## 🍎 URLSession e Alamofire (iOS)
- No iOS, `URLSession` é o nativo flexível.
- `Alamofire` é a biblioteca mais comum.
- `Codable` (iOS) == `Gson/Moshi` (Android).