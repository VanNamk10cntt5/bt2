# bt2
public class bai2 {
    public bai2() {
    }

    public class Vector {
        private double x;
        private double y;
        private double z;
    
        // Phương thức khởi tạo với 3 tham số
        public Vector(double x, double y, double z) {
            this.x = x;
            this.y = y;
            this.z = z;
        }
    
        // Phương thức lấy giá trị x
        public double getX() {
            return x;
        }
    
        // Phương thức lấy giá trị y
        public double getY() {
            return y;
        }
    
        // Phương thức lấy giá trị z
        public double getZ() {
            return z;
        }
    
        // Phương thức cộng 2 vector
        public Vector cong(Vector v) {
            return new Vector(x + v.getX(), y + v.getY(), z + v.getZ());
        }
    
        // Phương thức trừ 2 vector
        public Vector tru(Vector v) {
            return new Vector(x - v.getX(), y - v.getY(), z - v.getZ());
        }
    
        // Phương thức nhân vector với 1 hằng số
        public Vector nhan(double k) {
            return new Vector(k * x, k * y, k * z);
        }
    
        // Phương thức nhân vô hướng 2 vector
        public double nhanVH(Vector v) {
            return x * v.getX() + y * v.getY() + z * v.getZ();
        }
    }
    
    
}
