public class Criptografia{

    
    public String criptografar(String texto) {

        teste(texto);

        String text = texto.toLowerCase();
        StringBuilder saida = new StringBuilder();

        for (int i = 0; i < text.length(); i++) {

            int asc = text.charAt(i);
            if (asc >= 97 && asc <= 122) {
                asc += 3;
                Character c = (char) asc;
                saida.append(c);
            } else if (asc >= 48 && asc <= 57) {
                char c = (char) asc;
                saida.append(c);
            } else if (asc == 32) {
                saida.append(" ");
            }
        }
        return saida.toString();





    }

    
    public String descriptografar(String texto) {
        teste(texto);

        String text = texto.toLowerCase();
        StringBuilder saida = new StringBuilder();

        for(int i = 0; i < text.length(); i++){

            int asc = text.charAt(i);
            if(asc >= 97 && asc <= 122){
                asc -= 3;
                char c = (char)asc;
                saida.append(c);
            }
            else if(asc >= 48 && asc <= 57){
                char c = (char)asc;
                saida.append(c);
            }
            else if(asc == 32){
                saida.append(" ");
            }
        }
        return saida.toString();
    }

    static void teste(String texto){
        if(texto == ""){
            throw  new IllegalArgumentException("Texto nao pode ser vazio");
        }

    }

}
