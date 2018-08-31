import java.util.Arrays;

public class Arreglo {
    private int v[];

    public Arreglo (int n) {
        v = new int[n];
    }

    @Override
    public String toString() {
        return "Arreglo = " + Arrays.toString(v);
    }

    public void cargarArreglo () {
        for (int i = 0; i < v.length; i++) {
            v[i] = (int) Math.round(100 * Math.random());
        }
    }

    public boolean estaOrdenado () {
        for (int i = 0; i < v.length - 1; i++) {
            if (v[i] > v[i+1]) {
                return false;
            }
        }
        return true;
    }
}
