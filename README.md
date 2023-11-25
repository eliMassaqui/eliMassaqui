# Open Your World!

using UnityEngine;

public class UserProfile : MonoBehaviour
{
    // Informações pessoais
    string idade = "21 anos";
    string localizacao = "Luanda, Angola";
    string inicioProgramador = "2018";

    // Educação
    string universidade = "Primeiro Ano de Engenharia de Computação";

    // Habilidades
    string[] idiomas = { "Português", "Inglês" };
    string[] desenvolvimentoSoftware = { "Unity", "Android Studio" };
    string desenvolvimentoFrontEnd = "Web";

    // Experiência Profissional
    string cargo = "Desenvolvedor Unity e Android Studio";
    string[] responsabilidades = {
        "Desenvolvimento de jogos em Unity 3D e 2D",
        "Criação de aplicativos com Android Studio"
    };

    void Start()
    {
        MostrarPerfil();
    }

    void MostrarPerfil()
    {
        Debug.Log("🎂 Idade: " + idade);
        Debug.Log("🌍 Localização: " + localizacao);
        Debug.Log("📅 Início como Programador: " + inicioProgramador);
        Debug.Log("\n## 📚 Educação");
        Debug.Log("🎓 Universidade: " + universidade);
        Debug.Log("\n## 🚀 Habilidades");
        Debug.Log("🗣️ Idiomas: " + string.Join(", ", idiomas));
        Debug.Log("💻 Desenvolvimento de Software: " + string.Join(", ", desenvolvimentoSoftware));
        Debug.Log("🌐 Desenvolvimento Front-End: " + desenvolvimentoFrontEnd);
        Debug.Log("\n## 💼 Experiência Profissional");
        Debug.Log("👨‍💻 " + cargo);
        
        foreach (string responsabilidade in responsabilidades)
        {
            Debug.Log("  - " + responsabilidade);
        }
    }
}

 
 <h2>Tools & Technologies </h2>
<p>
   <br>
 [unity](https://github.com/elisioMassaqui/elisioMassaqui/assets/145590545/a88ee5b6-71e2-4376-96c1-bb22a40c25e3)
</p><br>

- 
<!---
elisioMassaqui/elisioMassaqui is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
