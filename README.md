# exp使用git管理代码
class Ticket:
    def __init__(self, price):
        self.price = price

    def purchase(self, quantity):
        total_cost = self.price * quantity
        print(f"您购买了{quantity}张票，总价为：{total_cost}元。")

def main():
    # 假设票价为100元
    ticket = Ticket(100)
    # 用户输入购买数量
    quantity = int(input("请输入您想购买的车票数量："))
    ticket.purchase(quantity)

if __name__ == "__main__":
    main()
