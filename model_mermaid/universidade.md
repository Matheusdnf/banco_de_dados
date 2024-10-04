```mermaid
erDiagram
%%%caso for vários centros é de muito para muitos
    Centro }|--|| Curso : cursos_do_centro
    Centro }|--|| Departamento : Departamento_do_centro
    Aluno ||--|{ curso: Matricula
```
