import org.junit.Test;
import static org.junit.Assert.assertEquals;

public class MathOperationsTest {

    @Test
    public void testAddition() {
        int result = add(5, 3);
        assertEquals(8, result);
    }

    @Test
    public void testSubtraction() {
        int result = subtract(10, 3);
        assertEquals(7, result);
    }

    @Test
    public void testMultiplication() {
        int result = multiply(4, 5);
        assertEquals(20, result);
    }

    @Test
    public void testDivision() {
        int result = divide(20, 4);
        assertEquals(5, result);
    }

    public int add(int a, int b) {
        return a + b;
    }

    public int subtract(int a, int b) {
        return a - b;
    }

    public int multiply(int a, int b) {
        return a * b;
    }

    public int divide(int a, int b) {
       
        return a / b;
    }
}
