    def calculate_percentages(self):
        total_percentages = 0
        for account in self.accounts:
            total_percentages += account.balance * (0.5 / 100)
        print(f"{self.name} {self.surname} iegūs {total_percentages:.2f} šajā gadā.")
