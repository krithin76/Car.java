package Car;

public class Showroom {
    public static void main(String[] args) {
        Car c1 = new Car("Nano", "200", 40000, 18.5);
        Car c2 = new Car("RR", "300", 60000, 20.0);
        Car c3 = new Car("BMW", "500", 242000, 35.0);

        c1.displayDetails();
        c2.displayDetails();
        c3.displayDetails();

        c1.setOwnerName("Alice"); 
        c1.UpdatePrice(16000);

        System.out.println("After Updates:");
        c1.displayDetails();

        Car.showShowroomName();
        Car.showTotalCars();
    }

}