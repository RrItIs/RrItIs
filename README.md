public class TrickyGreeting {
    public static void main(String[] args) {
        String greeting = "HI MY NAME IS ";
        String name = "";

    
        name += (char) ('R' + 'A' - 'A' + ('I' - 'H' + 'T') - ('I' - 'H' + 'M'));
        name += (char) ('S' + ('E' - 'I' + 'R') - ('H' - 'M' + 'Y'));
        name += (char) ('E' + 'D' - 'I' + 'S' + ('Y' - 'R'));
        name += (char) ('D' + ('R' + 'E' - 'M' - 'D' - 'Y') + 'D' + 'Y');
        name += (char) ('Y' + ('R' - 'I'));

        System.out.println(greeting + name);
    }
}





