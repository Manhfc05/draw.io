<?xml version="1.0" encoding="UTF-8"?>
<mxfile host="app.diagrams.net">
  <diagram id="UseCaseDiagram" name="Page-1">
    <mxGraphModel dx="1028" dy="647" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        
        <!-- Actor: Customer -->
        <mxCell id="customer" value="Customer" style="shape=umlActor;fillColor=#a3c8ff;" vertex="1" parent="1">
          <mxGeometry x="50" y="150" width="50" height="80" as="geometry" />
        </mxCell>

        <!-- Actor: Admin -->
        <mxCell id="admin" value="Admin" style="shape=umlActor;fillColor=#ffaaaa;" vertex="1" parent="1">
          <mxGeometry x="500" y="150" width="50" height="80" as="geometry" />
        </mxCell>

        <!-- Use Cases -->
        <mxCell id="register" value="Register" style="ellipse;fillColor=#ffffcc;" vertex="1" parent="1">
          <mxGeometry x="200" y="100" width="120" height="40" as="geometry" />
        </mxCell>
        <mxCell id="login" value="Login" style="ellipse;fillColor=#ffffcc;" vertex="1" parent="1">
          <mxGeometry x="200" y="160" width="120" height="40" as="geometry" />
        </mxCell>
        <mxCell id="browse" value="Browse Products" style="ellipse;fillColor=#ffffcc;" vertex="1" parent="1">
          <mxGeometry x="200" y="220" width="120" height="40" as="geometry" />
        </mxCell>
        <mxCell id="order" value="Place Order" style="ellipse;fillColor=#ffffcc;" vertex="1" parent="1">
          <mxGeometry x="200" y="280" width="120" height="40" as="geometry" />
        </mxCell>
        <mxCell id="payment" value="Make Payment" style="ellipse;fillColor=#ffffcc;" vertex="1" parent="1">
          <mxGeometry x="200" y="340" width="120" height="40" as="geometry" />
        </mxCell>

        <mxCell id="manage_products" value="Manage Products" style="ellipse;fillColor=#ffcc99;" vertex="1" parent="1">
          <mxGeometry x="350" y="100" width="140" height="40" as="geometry" />
        </mxCell>
        <mxCell id="manage_orders" value="Manage Orders" style="ellipse;fillColor=#ffcc99;" vertex="1" parent="1">
          <mxGeometry x="350" y="160" width="140" height="40" as="geometry" />
        </mxCell>
        <mxCell id="manage_users" value="Manage Users" style="ellipse;fillColor=#ffcc99;" vertex="1" parent="1">
          <mxGeometry x="350" y="220" width="140" height="40" as="geometry" />
        </mxCell>

        <!-- Connections -->
        <mxCell id="edge1" edge="1" parent="1" source="customer" target="register">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge2" edge="1" parent="1" source="customer" target="login">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge3" edge="1" parent="1" source="customer" target="browse">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge4" edge="1" parent="1" source="customer" target="order">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge5" edge="1" parent="1" source="customer" target="payment">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

        <mxCell id="edge6" edge="1" parent="1" source="admin" target="manage_products">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge7" edge="1" parent="1" source="admin" target="manage_orders">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="edge8" edge="1" parent="1" source="admin" target="manage_users">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
