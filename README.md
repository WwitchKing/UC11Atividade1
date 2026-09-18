# Nome do Projeto 

Leloes TDS - UC11 Atividade 1

## Explicação do Projeto

Projeto feito em Java, utilizando Banco de Dados e usado para praticar o versionamente local e remoto

## Tecnilogias utilizadas

- Java
- MySQL

  ## Exemplo de código de conexão

  ```public Connection connectDB(){
        Connection conn = null;
        
        try {
        
            conn = DriverManager.getConnection("jdbc:mysql://localhost/uc11?user=root&password=");
            
        } catch (SQLException erro){
            JOptionPane.showMessageDialog(null, "Erro ConectaDAO" + erro.getMessage());
        }
        return conn;
    }
    
}
```
