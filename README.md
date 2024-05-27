class Airplane {
    constructor(name) {
        this.name = name;
        this.isFlying = false;
    }

    takeOff() {
        this.isFlying = true;
    }

    land() {
        this.isFlying = false;
    }
}
