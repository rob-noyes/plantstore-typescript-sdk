# Reference

## plant

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">addPlant</a>({ ...params }) -> RobertNoyes.PlantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.addPlant({
    name: "Fern",
    category: "Indoor",
    tags: ["green", "leafy"],
    status: "available",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.Plant`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">updatePlant</a>({ ...params }) -> RobertNoyes.PlantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.updatePlant({
    name: "Fern",
    category: "Indoor",
    tags: ["green", "leafy"],
    status: "sold",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.Plant`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">searchPlantsByStatus</a>({ ...params }) -> RobertNoyes.PlantResponse[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Filter plants based on their current status.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.searchPlantsByStatus();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.SearchPlantsByStatusRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">searchPlantsByTags</a>({ ...params }) -> RobertNoyes.PlantResponse[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Filter plants based on associated tags.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.searchPlantsByTags();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.SearchPlantsByTagsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">getPlantById</a>({ ...params }) -> RobertNoyes.PlantResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a plant's details by its ID.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.getPlantById({
    plantId: 1,
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.GetPlantByIdRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## user

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">loginUser</a>({ ...params }) -> RobertNoyes.UserAuthResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.loginUser();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.LoginUserRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">logoutUser</a>() -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.logoutUser();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">getUserByName</a>({ ...params }) -> RobertNoyes.User</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve user details using their username.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.getUserByName({
    username: "username",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyes.GetUserByNameRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>
